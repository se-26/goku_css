#  Galería Visual Dragon Ball Z

## Descripción del Proyecto

Este proyecto es una **galería visual interactiva** que demuestra el dominio completo de propiedades visuales en CSS, incluyendo colores, gradientes, imágenes de fondo y transparencias. La galería presenta **26 personajes de Dragon Ball Z**, cada uno con su propia imagen y efectos CSS únicos.

##  Características Principales

### Propiedades CSS Implementadas

 **Colores en 5 formatos diferentes:**
- Hexadecimal (`#FFD700`)
- Nombres CSS (`royalblue`)
- RGB (`rgb(46, 204, 113)`)
- RGBA con transparencia (`rgba(155, 89, 182, 0.9)`)
- RGB con porcentajes (`rgb(5%, 50%, 95%)`)

**Gradientes:**
- Lineales horizontales (`linear-gradient(to right, ...)`)
- Lineales diagonales (`linear-gradient(135deg, ...)`)
- Radiales circulares (`radial-gradient(circle, ...)`)
- Gradientes múltiples con varios color-stops
- **26 overlays únicos** con diferentes efectos visuales

 **Imágenes de Fondo:**
- `background-image: url()` - 26 imágenes diferentes
- `background-size: cover`
- `background-position: center`
- `background-repeat: no-repeat`
- `background-attachment: fixed` (efecto parallax)

 **Transparencias y Overlays:**
- Capas semitransparentes con `rgba()`
- Efecto de desenfoque con `backdrop-filter`
- Diferentes niveles de opacidad para cada personaje

##  Personajes Incluidos (26 en total)

### Héroes
1. **Goku** (goku_normal.webp) - El protagonista principal
2. **Gohan** (gohan.webp) - El guerrero místico
3. **Bardock** (Bardock_Artwork.webp) - El padre de Goku
4. **Gotenks** (Gotenks_Artwork.webp) - La fusión poderosa

### Villanos
5. **Freezer** (Freezer.webp) - El emperador del universo
6. **Cell** (celula.webp) - El bio-androide perfecto
7. **Majin Buu** (BuuGordo_Univerdo7.webp) - El demonio rosa
8. **Beerus** (Beerus_DBS_Artwork.webp) - Dios de la destrucción

### Androides
9. **Android 18** (Android _18_Artwork.webp) - La guerrera cibernética
10. **Android 16** (Android_16.webp) - El androide pacifista
11. **Android 19** (Android19.webp) - Absorbe energía
12. **Dr. Gero** (Dr._Gero_nadroide_20.webp) - Android 20
13. **Android 13** (Android13normal.webp) - Diseñado para matar
14. **Android 17** (17_Artwork.webp) - El guardabosques

### Fuerzas Especiales
15. **Capitán Ginyu** (Ginyu.webp) - Líder de las fuerzas
16. **Dodoria** (dodoria.webp) - Guerrero élite de Freezer

### Personajes de Soporte
17. **Babidi** (Babidi_Artwork.webp) - El hechicero maligno
18. **Dende (Super Hero)** (Arte_de_Dende_en_super_Hero.webp)
19. **Dende** (Dende_Artwork.webp) - Guardián de la Tierra
20. **Bulma** (bulma.webp) - La científica genio
21. **Chi-Chi** (ChiChi_DBS.webp) - Esposa de Goku
22. **Yamcha** (Final_Yamcha.webp) - Guerrero del desierto
23. **Gran Kaio Sama** (Gran_kaio_sama12.webp) - Maestro supremo

### Guerreros Especiales
24. **Dyspo** (Dispo_render.webp) - Guerrero de la velocidad

### Artworks Dokkan
25. **Dokkan 14** (14Dokkan.webp) - Ilustración especial
26. **Dokkan 15** (15Dokkan.webp) - Ilustración coleccionable

##  Cómo Ver el Proyecto

### Opción 1: Ver en Local

1. Clona este repositorio:
```bash
git clone  https://github.com/se-26/goku.git
```

2. Navega a la carpeta del proyecto:
```bash
cd galeria-visual-transferencia
```

3. Asegúrate de tener todas las imágenes en la carpeta raíz:
   - 14Dokkan.webp
   - 15Dokkan.webp
   - 17_Artwork.webp
   - Android19.webp
   - Android_16.webp
   - Android _18_Artwork.webp
   - Android13normal.webp
   - Arte_de_Dende_en_super_Hero.webp
   - Babidi_Artwork.webp
   - Bardock_Artwork.webp
   - Beerus_DBS_Artwork.webp
   - bulma.webp
   - BuuGordo_Univerdo7.webp
   - celula.webp
   - ChiChi_DBS.webp
   - Dende_Artwork.webp
   - Dispo_render.webp
   - dodoria.webp
   - Dr._Gero_nadroide_20.webp
   - Final_Yamcha.webp
   - Freezer.webp
   - Ginyu.webp
   - gohan.webp
   - goku_normal.webp
   - Gotenks_Artwork.webp
   - Gran_kaio_sama12.webp

4. Abre el archivo `index.html` en tu navegador favorito

### Opción 2: Ver en GitHub Pages

 **URL del proyecto:** [ https://github.com/se-26/goku.git]( https://github.com/se-26/goku.git)

##  Estructura del Proyecto

```
galeria-visual-transferencia/
│
├── index.html                              # Página principal de la galería
├── styles.css                              # Estilos CSS con todas las propiedades
├── README.md                               # Este archivo
├── .gitignore                              # Archivos ignorados por Git
│
├── goku_normal.webp                        # Imágenes de personajes
├── gohan.webp
├── Bardock_Artwork.webp
├── Gotenks_Artwork.webp
├── Freezer.webp
├── celula.webp
├── BuuGordo_Univerdo7.webp
├── Beerus_DBS_Artwork.webp
├── Android _18_Artwork.webp
├── Android_16.webp
├── Android19.webp
├── Dr._Gero_nadroide_20.webp
├── Android13normal.webp
├── 17_Artwork.webp
├── Ginyu.webp
├── dodoria.webp
├── Babidi_Artwork.webp
├── Arte_de_Dende_en_super_Hero.webp
├── Dende_Artwork.webp
├── bulma.webp
├── ChiChi_DBS.webp
├── Final_Yamcha.webp
├── Gran_kaio_sama12.webp
├── Dispo_render.webp
├── 14Dokkan.webp
└── 15Dokkan.webp
```

##  Decisiones de Diseño

### Paleta de Colores

La paleta fue cuidadosamente seleccionada para reflejar las diferentes transformaciones y energías de Dragon Ball Z:

1. **Dorado Saiyajin** (`#FFD700`) - Representa el icónico Super Saiyajin
2. **Azul Real** (`royalblue`) - Inspirado en el Super Saiyajin Blue
3. **Verde Namek** (`rgb(46, 204, 113)`) - Color característico de Namek
4. **Púrpura Majin** (`rgba(155, 89, 182, 0.9)`) - Basado en la energía Majin
5. **Azul Kamehameha** (`rgb(5%, 50%, 95%)`) - El color del ataque más famoso

### Overlays Personalizados

Cada uno de los 26 personajes tiene un overlay único diseñado específicamente para complementar su imagen:

- **Gradientes lineales** para personajes dinámicos
- **Gradientes radiales** para efectos de energía y auras
- **Colores temáticos** que reflejan la personalidad de cada personaje
- **Diferentes niveles de opacidad** para optimizar la legibilidad

### Optimización de Imágenes

- Uso de formato `.webp` para mejor compresión y calidad
- Cada imagen está configurada con `background-size: cover`
- Overlays semi-transparentes para garantizar legibilidad del texto
- Efectos hover suaves para mejor experiencia de usuario

##  Técnicas CSS Destacadas

### 1. Variables CSS
```css
:root {
    --color-saiyan: #FFD700;
    --color-ocean: royalblue;
    --spacing-large: 40px;
}
```

### 2. Overlays Únicos con RGBA
```css
.overlay-1 {
    background: linear-gradient(135deg, 
        rgba(243, 156, 18, 0.7), 
        rgba(230, 126, 34, 0.7)
    );
}
```

### 3. Imágenes Inline con Background
```css
<article class="gallery-item" 
    style="background-image: url('goku_normal.webp');">
```

### 4. Efecto Parallax
```css
background-attachment: fixed;
```

### 5. Transiciones Suaves
```css
transition: all 0.3s ease;
```

##  Objetivos de Aprendizaje Alcanzados

 Aplicar colores usando 5 notaciones diferentes de CSS  
 Crear gradientes lineales y radiales complejos  
 Configurar 26 imágenes de fondo con propiedades avanzadas  
 Implementar 26 overlays únicos con transparencias  
 Garantizar legibilidad con alto contraste  
 Organizar código CSS con comentarios descriptivos  
 Crear interfaces completamente responsivas  
 Documentar decisiones de diseño profesionalmente  
 Superar el requisito mínimo de 20 recursos visuales  

##  Responsive Design

El proyecto está optimizado para diferentes tamaños de pantalla:

- **Desktop**: Grid de 3-4 columnas
- **Tablet**: Grid de 2 columnas  
- **Mobile**: Grid de 1 columna

Media queries implementados:
```css
@media (max-width: 768px) { /* Estilos tablet */ }
@media (max-width: 480px) { /* Estilos móvil */ }
```

##  Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Propiedades visuales avanzadas
  - Gradientes lineales y radiales
  - Transparencias RGBA
  - Variables CSS
  - Flexbox y Grid
  - Transiciones y animaciones
- **Git**: Control de versiones
- **GitHub Pages**: Hosting gratuito

## Recursos de Referencia

- [MDN Web Docs - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [CSS-Tricks](https://css-tricks.com/)
- [W3Schools CSS Reference](https://www.w3schools.com/cssref/)
- [Google Fonts](https://fonts.google.com/)
- [WebP Image Format](https://developers.google.com/speed/webp)

##  Autor

**[selena molina]**  
Técnico en Programación de Software - SENA  
Ficha: [3315656]  
Instructor: John Freddy Becerra Castellanos

## Detalles Técnicos del Proyecto

### Estadísticas
- **Total de personajes**: 26
- **Total de overlays únicos**: 26
- **Formatos de color usados**: 5
- **Tipos de gradientes**: 3 (lineal, radial, múltiple)
- **Líneas de CSS**: ~900+
- **Propiedades background aplicadas**: 130+ (5 por imagen)

### Cumplimiento de Requisitos

 **Estructura del proyecto**: Repositorio en GitHub configurado  
**README.md**: Documentación completa incluida  
**GitHub Pages**: Preparado para publicación  
 **Contenido de la galería**: 26 recursos (supera mínimo de 20)  
 **Uso de CSS**: Paleta definida y aplicada  
 **Gradientes**: Implementados en múltiples secciones  
 **Imágenes de fondo**: 26 imágenes correctamente configuradas  
 **Transparencias**: RGBA aplicado en todos los overlays  
 **Contraste**: Alto contraste garantizado en todo el sitio  
 **Documentación del código**: Comentarios explicativos completos  
**Decisiones de diseño**: Documentadas en README.md  
 Agradecimientos

- Al instructor John Freddy Becerra Castellanos por la guía y formación
- Al SENA - CIMI por proporcionar el programa educativo
- A la comunidad de desarrolladores web por los recursos compartidos
- A Akira Toriyama por crear el universo de Dragon Ball

## Licencia

Este proyecto fue creado con fines educativos como parte del programa de formación del SENA. Las imágenes de Dragon Ball son propiedad de sus respectivos dueños y se utilizan únicamente con propósitos educativos.

---

**Fecha de entrega:** [8/12/2025]  
**Programa:** Técnico en Programación de Software  
**Centro:** CIMI - SENA  
**Fase del Proyecto:** Ejecución  
**Actividad:** Introducción al diseño de aplicaciones web

##  Highlights del Proyecto

### Lo que hace único este proyecto:

1. **26 personajes diferentes** - Cada uno con su propia imagen única
2. **26 overlays personalizados** - Diseñados específicamente para cada personaje
3. **Formato WebP** - Imágenes optimizadas para web
4. **100% Responsive** - Funciona perfectamente en todos los dispositivos
5. **Código completamente documentado** - Cada sección explicada
6. **Cumple y supera los requisitos** - 26 recursos vs 20 requeridos

---

**¡Gracias por revisar este proyecto!** 