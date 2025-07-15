<p align="center">
  <img src="https://avatars.githubusercontent.com/u/72231436?v=4" alt="Avatar" width="120" style="border-radius: 50%;" />
</p>

# Simple-Flyer-Digital

> **“Tu escaparate digital, presentado con estilo futurista.”**

---

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 🧠 Descripción general

Simple-Flyer-Digital es un folleto interactivo vertical diseñado para tablets de mostrador, enfocado en potenciar la presencia online de las pequeñas y medianas empresas peruanas. Con una estructura modular en HTML, CSS y JavaScript, ofrece una experiencia inmersiva que combina animaciones suaves, paleta de neones y componentes glassmorphism para destacar productos, planes y hoja de ruta en un solo lugar.

---

## 🛠️ Historia del desarrollo

### 🔹 Plan inicial

* Crear un diseño limpio y llamativo usando una paleta oscura con destellos de neón.
* Implementar glassmorphism para tarjetas de contenido (features, eventos, planes).
* Añadir animaciones CSS para dar vida a secciones clave: hero, timeline y pricing.

### 🔹 Dificultades encontradas

* Ajustar el layout responsivo para tablets verticales sin sacrificar la legibilidad.
* Sincronizar animaciones CSS en background con el contenido principal sin afectar el rendimiento.
* Equilibrar el contraste entre colores neón y textos legibles en entornos de baja luminosidad.

### 🔹 Solución final adoptada

* **Layout fluido con `container` y `grid` CSS** optimizado para pantallas de hasta 600 px de ancho.
* **Animaciones con `@keyframes`** y timing easings para un desplazamiento armónico.
* **Feather Icons** dinamizado con JavaScript para cargar los íconos al vuelo.
* **Glassmorphism** aplicado a tarjetas y eventos, con backdrop-filter y opacidades controladas.

---

## 📋 Estructura del proyecto

```
Simple-Flyer-Digital/
├── index.html
├── README.md
├── LICENSE
└── assets/
    ├── css/
    │   └── styles.css
    └── js/
        └── main.js
```

---

## 🚶‍♂️ Paso a paso del desarrollo

1. **Estructura HTML**

   * Maquetación semántica de secciones: `<header>`, `<section>` y `<footer>`.
   * Uso de comentarios para delimitar bloques: HERO, FEATURES, TIMELINE, PRICING, CTA.

2. **Estilos con CSS puro**

   * Definición de variables CSS en `:root` (colores, radios, tipografías).
   * Glassmorphism en `.glass` con `backdrop-filter: blur()` y bordes semitransparentes.
   * Grid layouts para `.feature-grid` y `.pricing-grid`.
   * Animaciones `@keyframes` para fondos flotantes y planos con efecto levitación.

3. **Animaciones y comportamiento**

   * Fondo animado en `<header>` con pseudo-elementos difuminados.
   * Efecto “pulse” en botones CTA usando `animation` y `transform: scale()`.
   * Feather Icons cargadas dinámicamente al final del `<body>` con `feather.replace()`.

4. **Optimización responsive**

   * `width: min(92%, 600px)` en `.container` para adaptarse a tablets verticales.
   * Tipografías “Poppins” y “Bebas Neue” importadas desde Google Fonts.
   * Meta viewport configurado para garantizar escala adecuada en dispositivos.

---

## 💾 Instalación y uso

### 1. Clona el repositorio

```bash
git clone https://github.com/tu-usuario/Simple-Flyer-Digital.git
cd Simple-Flyer-Digital
```

### 2. Abre `index.html`

No se requieren dependencias externas; basta con abrir el archivo en tu navegador o emplear un servidor local:

```bash
# Opcional: usar un servidor HTTP simple
python -m http.server 8000
# y luego visita http://localhost:8000
```

---

## ✅ Cómo usarlo

1. Desplázate verticalmente para navegar entre secciones:

   * **Hero:** título y enlace a demo.
   * **Features:** beneficios instantáneos.
   * **Timeline:** hoja de ruta de 2025 a 2027.
   * **Pricing:** planes Seed, Grow y Bloom-AI.
   * **CTA:** llamado a la acción final.

2. Haz clic en el botón “Ver Demo” para acceder a la demo alojada.

3. Personaliza textos, colores y enlaces editando `index.html` y `assets/css/styles.css`.

---

## 📌 Consideraciones técnicas

* Totalmente libre de frameworks: cero dependencias.
* Funciona offline salvo carga de Google Fonts y Feather Icons.
* Ideal para instalación en tablets de mostrador o kioscos informativos.

---

## 🧪 Pruebas y desarrollo

* Verifica la compatibilidad en Chrome, Safari y Edge en modo tablet.
* Emplea herramientas de Lighthouse para medir rendimiento y accesibilidad.
* Ejecuta la demo en distintos niveles de brillo para validar contraste.

---

## 📝 Licencia

MIT License. Puedes usar, modificar y redistribuir este proyecto libremente.

---

## 👨‍💻 Autor

[![avatar](https://avatars.githubusercontent.com/u/72231436?v=4)](https://github.com/sjaquer)

Desarrollado por **sjaquer**
Repositorio original: [github.com/sjaquer/Simple-Flyer-Digital](https://github.com/sjaquer/Simple-Flyer-Digital)
