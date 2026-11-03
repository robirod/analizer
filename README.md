# Analizer.html 📊🎵

**Analizer.html** es un visualizador de espectro en tiempo real diseñado para demostrar de forma rápida y visual la **Transformada Rápida de Fourier (FFT)**. El proyecto nace de la necesidad de contar con una herramienta educativa, ligera y portátil, capaz de ejecutarse de manera inmediata en cualquier dispositivo o navegador web sin depender de la instalación de software especializado, DAWs (Digital Audio Workstations) o plugins externos.

---

## ✨ Características Principales

*   **Rango de Espectro Completo:** Visualización fluida que cubre todo el rango audible humano, desde **20 Hz hasta 20 kHz**.
*   **Escala Logarítmica Visual:** Optimizado matemáticamente para que las frecuencias bajas y medias (como la voz humana) se aprecien con total claridad en pantalla, evitando la compresión lineal.
*   **100% Portátil y Ligero:** Todo el proyecto vive en un único archivo de código nativo (HTML5 + JavaScript). Sin dependencias, sin frameworks pesados ni librerías de terceros.
*   **Compatibilidad Universal:** Funciona al instante en cualquier navegador moderno (Safari, Chrome, Firefox, Edge) en entornos de escritorio y móviles gracias a la **Web Audio API** estándar.
*   **Estética Moderna:** Interfaz con diseño oscuro de alto contraste y gradientes de color dinámicos basados en la frecuencia e intensidad de la señal, ideal para proyecciones y presentaciones en vivo.

---

## 🚀 Instalación y Uso Rápido

Al ser una herramienta puramente de lado del cliente (*client-side*), tienes dos formas muy sencillas de utilizarlo:

### Opción 1: Uso Local (En tu computadora)
1. Descarga o clona este repositorio.
2. Haz doble clic en el archivo `index.html` para abrirlo en tu navegador favorito.
3. Haz clic en **"Activar Micrófono"**, otorga los permisos necesarios y empieza a hablar o emitir señales.

### Opción 2: Despliegue en la Web (Ideal para presentaciones)
Puedes activar **GitHub Pages** en este mismo repositorio para tener una URL pública en un par de clics:
1. Ve a la pestaña **Settings** de tu repositorio de GitHub.
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En la sección *Build and deployment*, selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
4. Haz clic en **Save**. ¡Listo! En unos segundos tendrás tu enlace público listo para presentar desde cualquier equipo con internet.

---

## 🛠️ Tecnologías Utilizadas

*   **HTML5 & CSS3:** Estructura limpia y diseño responsivo adaptado al tamaño de la pantalla.
*   **Web Audio API:** Manipulación e ingeniería de audio en tiempo real nativa del navegador mediante nodos `AnalyserNode` y un tamaño de FFT denso de `4096` bins para máxima resolución.
*   **HTML5 Canvas API:** Renderizado de gráficos de alta velocidad cuadro por cuadro utilizando `requestAnimationFrame`.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Siéntete libre de clonarlo, modificarlo y adaptarlo para tus propias clases, presentaciones o proyectos de análisis de señales.
