### INSTRUCCIONES GENERALES

Crea un proyecto web interactivo para un curso universitario de "Análisis y Diseño de Sistemas de Información". El proyecto debe ser una aplicación web estática (HTML/CSS/JavaScript puro) que funcione abriendo los archivos directamente en el navegador, sin necesidad de servidor.

**Universidad:** UniSalamanca
**Periodo:** 2026-2
**Curso:** Análisis y Diseño de Sistemas de Información
**Profesor:** MAURICIO JAVIER BERTEL DOMINGUEZ
**Grupo:** 4

**Integrantes:**
- Jeimy Calderón
- Jorge Montiel
- Kevin Morales
- Raúl Lozano

### DISEÑO VISUAL

**Paleta de colores:**
- Fondo principal: #1f2937 (gris oscuro)
- Headers: Gradiente de #1e3a8a a #2563eb (azul rey)
- Acentos: #3b82f6 (azul claro), #fbbf24 (amarillo/dorado)
- Módulo Sistemas: #1a56db (azul)
- Módulo Información: #7c3aed (púrpura)
- Módulo Sistemas de Información: #0d9488 (teal)

**Tipografía:** Segoe UI, system-ui, sans-serif
**Estilo:** Moderno, con bordes redondeados, sombras suaves, transiciones en hover
**Responsive:** Diseño adaptable a desktop, tablet y móvil

### ARCHIVOS A CREAR

#### 1. index.html - Menú Principal

Página de inicio con:
- Header con logo "UniSalamanca" (icono cuadrado "US" + texto)
- Título principal: "Sistemas de Información"
- Subtítulo: "Introducción al Desarrollo · Elige cómo explorar"
- 3 tarjetas clickeables:
  1. 🎮 Juego del Laberinto (enlaza a game.html)
  2. 📊 Presentación (enlaza a presentacion.html)
  3. 🧠 Quiz Directo (enlaza a quiz.html)
- Footer con nombres de integrantes
- Efectos hover: elevación + sombra en tarjetas

#### 2. game.html - Juego del Laberinto

Juego educativo con canvas donde el jugador explora un laberinto recogiendo conceptos.

**Características:**
- Laberinto de 23x15 celdas, cada celda de 44px
- 15 conceptos coleccionables distribuidos en 3 módulos:
  - Módulo Sistemas (5 conceptos, color azul #1a56db)
  - Módulo Información (5 conceptos, color púrpura #7c3aed)
  - Módulo Sistemas de Información (5 conceptos, color teal #0d9488)
- Portales de teletransporte (2 portales)
- Minimapa en tiempo real (esquina inferior derecha)
- HUD con contador de conceptos y puntos
- Barra inferior mostrando todos los conceptos recogidos

**Controles:**
- Teclado: WASD o Flechas
- Touch: Swipe para móviles

**Eventos:**
- Al tocar un concepto: Popup con emoji, módulo, título y descripción
- Al llegar a la salida: Popup de completion con puntaje total
- Portales: Teletransportan al otro portal

**Conceptos del juego (15 total):**

Módulo SISTEMAS:
1. ⚙️ Concepto de Sistema - Conjunto de elementos interrelacionados para lograr un objetivo
2. 🔍 Análisis de Sistemas - Estudiar procedimientos para identificar QUÉ debe hacer el sistema
3. ✏️ Diseño de Sistemas - Especificar CÓMO hará el sistema lo que se necesita
4. 👥 Usuarios - Finales, gerenciales, técnicos y stakeholders
5. 🧩 Elementos - Entradas → Proceso → Salidas + Retroalimentación
6. 🔧 Características - Holismo, equifinalidad, homeostasis, adaptación, entropía

Módulo INFORMACIÓN:
7. 💎 Definición - Datos procesados y organizados con significado y utilidad
8. ⏱️ Oportunidad - Disponible cuando se necesita. Info tardía = inútil
9. 🎯 Precisión - Correcta y confiable. Errores = malas decisiones
10. 📝 Relevancia - Pertinente al propósito para el que se necesita
11. 🔄 Tratamiento - Captura → Validación → Transformación → Almacenamiento → Distribución

Módulo SISTEMAS DE INFORMACIÓN:
12. 🌐 Definición - Agentes, códigos y procesos que interactúan coordinadamente
13. 📊 Tipos (Pirámide) - TPS → MIS → DSS → EIS. Operativo a estratégico
14. 📋 Ciclo de Vida - Conocer → Diagnosticar → Diseñar → Codificar → Implementar
15. 🎯 Decisión e Información - Calidad de info determina efectividad de decisiones

**Diseño del laberinto:**
- Paredes: Color #94a3b8 con sombra inferior
- Suelo: Color #e2e8f0
- Conceptos: Emoji 💎 con brillo púrpura animado
- Portales: Emoji 🌀 con borde teal animado
- Salida: Emoji ⭐ con borde naranja animado
- Jugador: Círculo azul #1a56db con brillo y punto blanco

**Popup de concepto:**
- Emoji grande arriba
- Nombre del módulo en color
- Título del concepto en color
- Descripción del concepto
- Botón "Continuar →" en color del módulo

#### 3. presentacion.html - Presentación de 17 Diapositivas

Presentación tipo slideshow con navegación por teclado y botones.

**Características:**
- 17 diapositivas numeradas
- Navegación: Flechas ← → del teclado + botones en pantalla
- Transiciones suaves entre slides
- Progreso visual (barra o indicador)
- SVG animados para diagramas

**Estructura de las 17 diapositivas:**

1. Portada - "Introducción al Desarrollo de Sistemas de Información"
2. Contenido - Tabla de contenidos de los 3 módulos
3. Módulo 1: Sistemas - Título del módulo
4. Concepto de Sistema - Definición y elementos
5. Análisis y Diseño - Diferencia entre análisis y diseño
6. Usuarios - Tipos de usuarios del sistema
7. Elementos del Sistema - Entradas, proceso, salidas, retroalimentación
8. Características - Holismo, equifinalidad, homeostasis, etc.
9. Tipos de Sistemas - Abiertos, cerrados, etc.
10. Módulo 2: Información - Título del módulo
11. Definición de Información - Datos con significado
12. Características - Oportunidad, precisión, relevancia
13. Tratamiento de Datos - Proceso de captura a distribución
14. Módulo 3: Sistemas de Información - Título del módulo
15. Definición SI - Agentes y procesos coordinados
16. Tipos de SI - Pirámide TPS, MIS, DSS, EIS
17. Conclusión y Referencias

**Diagramas SVG animados:**
- Diagrama de flujo del sistema (Entrada → Proceso → Salida)
- Diagrama de información (Datos → Proceso → Información)
- Pirámide organizacional interactiva
- Ciclo de vida del sistema de información

#### 4. quiz.html - Evaluación Interactiva

Quiz con 10 preguntas de selección múltiple.

**Características:**
- 10 preguntas sobre los 3 módulos
- 4 opciones por pregunta (A, B, C, D)
- Retroalimentación inmediata al seleccionar:
  - ✅ Correcto: Mensaje de acierto en verde
  - ❌ Incorrecto: Mensaje de error en rojo + respuesta correcta
- Botón "Siguiente pregunta" después de responder
- Pantalla final con puntaje y porcentaje
- Botón "Volver al menú" y "Intentar de nuevo"

**Preguntas del quiz (ejemplo):**

1. ¿Qué es un sistema?
   - Conjunto de elementos interrelacionados ✓
   - Solo software y hardware
   - Un tipo de base de datos
   - Un programa de cómputo

2. ¿Cuál es la diferencia entre análisis y diseño?
   - Análisis = QUÉ, Diseño = CÓMO ✓
   - Análisis = CÓMO, Diseño = QUÉ
   - Son lo mismo
   - Análisis es para hardware, diseño para software

3. ¿Qué es la información oportuna?
   - Disponible cuando se necesita ✓
   - La más barata
   - La que tiene más datos
   - La que se genera primero

4. ¿Qué significa "tratamiento de datos"?
   - Captura → Validación → Transformación → Almacenamiento → Distribución ✓
   - Solo guardar datos en disco
   - Borrar información innecesaria
   - Crear copias de seguridad

5. ¿Qué es un sistema de información?
   - Agentes, códigos y procesos que interactúan coordinadamente ✓
   - Solo el hardware de cómputo
   - Un tipo de base de datos
   - Un programa específico

6. ¿Qué representa la pirámide de sistemas de información?
   - TPS → MIS → DSS → EIS ✓
   - Los niveles de usuario
   - Los tipos de hardware
   - Las fases del desarrollo

7. ¿Cuáles son los elementos de un sistema?
   - Entradas, Proceso, Salidas, Retroalimentación ✓
   - Solo entradas y salidas
   - Hardware y Software
   - Usuarios y administradores

8. ¿Qué es la homeostasis en sistemas?
   - Capacidad de mantener equilibrio interno ✓
   - Fallo del sistema
   - Tipo de virus
   - Actualización automática

9. ¿Qué determina la efectividad de las decisiones?
   - La calidad de la información ✓
   - La cantidad de usuarios
   - El precio del sistema
   - La velocidad del hardware

10. ¿Cuáles son los tipos de usuarios?
    - Finales, gerenciales, técnicos y stakeholders ✓
    - Solo usuarios finales
    - Administradores y programadores
    - Humanos y máquinas

### TECNOLOGÍAS A UTILIZAR

- **HTML5** - Estructura semántica
- **CSS3** - Estilos inline (sin archivos externos)
  - Flexbox y Grid para layouts
  - Transiciones y animaciones
  - Media queries para responsive
- **JavaScript** - Scripts inline (sin archivos externos)
  - Canvas API para el juego
  - DOM manipulation para interactividad
  - Event listeners para navegación
- **SVG** - Diagramas animados en la presentación

### CONSIDERACIONES IMPORTANTES

1. **Sin dependencias externas:** Todo debe funcionar offline, sin CDN, sin frameworks
2. **Archivos independientes:** Cada HTML es autocontenido con sus estilos y scripts
3. **Navegación entre archivos:** Usar enlaces relativos (game.html, presentacion.html, quiz.html)
4. **Responsive:** Diseño adaptable a todos los tamaños de pantalla
5. **Accesibilidad:** Contraste adecuado, tamaños de fuente legibles
6. **Consistencia visual:** Mismo header y footer en todas las páginas
7. **Branding:** Logo "UniSalamanca" visible en todas las páginas

### ESTILO DE CÓDIGO

- CSS inline dentro de `<style>` en cada archivo
- JavaScript inline dentro de `<script>` al final del body
- Nombres de clases descriptivos en inglés
- Sin comentarios en el código
- Código minificado pero legible
- Variables CSS para colores principales

---

## Resumen de Especificaciones

| Componente | Especificación |
|------------|----------------|
| Archivos | 4 HTML + 1 README |
| Juego | Canvas 23x15, 15 conceptos, 3 módulos |
| Presentación | 17 slides, SVG animados, navegación teclado |
| Quiz | 10 preguntas, 4 opciones, retroalimentación |
| Diseño | Dark theme, azul rey, responsive |
| Tecnología | HTML5 + CSS3 + JavaScript vanilla |
| Dependencias | Ninguna (funciona offline) |

---

## Instrucciones Finales

Genera los 4 archivos HTML (index.html, game.html, presentacion.html, quiz.html) y el README.md siguiendo todas las especificaciones anteriores. Asegúrate de que:

1. Cada archivo sea autocontenido (CSS y JS inline)
2. Los enlaces entre archivos funcionen correctamente
3. El juego sea jugable y educativo
4. La presentación tenga animaciones SVG
5. El quiz funcione con retroalimentación inmediata
6. Todo sea responsive y tenga buen diseño visual
7. Los conceptos educativos sean correctos y completos
8. El branding de UniSalamanca sea consistente

**El resultado debe ser un proyecto web completo, funcional y profesional para presentar en clase.**