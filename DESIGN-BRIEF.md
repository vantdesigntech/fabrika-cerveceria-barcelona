# DESIGN BRIEF — LA FÀBRIKA DEL POBLENOU (Cervecería Artesana de Barcelona · Inspirada en Awwwards "About Us - Faktory")

> Documento estructurado en los 7 bloques obligatorios de [`creative_brief_builder.html`](file:///C:/Users/Jose/Downloads/creative_brief_builder.html) tras inspeccionar en vivo `https://www.awwwards.com/inspiration/about-us-faktory` y `https://faktory.fr/a-propos/`.

---

## 01 · Proyecto
- **Nombre del proyecto:** `FÀBRIKA — Cerveseria Artesana & Taproom Social (Barcelona)`
- **Tipo de web / sector:** Cervecería artesanal independiente, fábrica de cerveza de tirada directa, *taproom* gastronómico de brasa y espacio cultural en el barrio de El Poblenou, Barcelona.
- **Objetivo y público:** Transmitir el carácter social, industrial y festivo de una auténtica fábrica de cerveza barcelonesa nacida en una antigua nave textil de Poblenou en 2012, manteniendo al 100% la dirección de arte tipográfica y cromática de *Faktory* (Awwwards).
- **Dirección visual general:**
  - Tipografía **maximalista ultra-condensada** que combina bloques masivos en `Mango Grotesk Title` con párrafos monumentales ultra-finos y altos en `Mango Grotesk`.
  - Contraste cromático de alto voltaje entre **Azul Petróleo Nocturno (`#0B252F`)**, **Naranja Terracota Eléctrico (`#FF6233`)**, **Burdeos Malta Tostada (`#4D0007` / `#780F18`)**, **Crema Espuma (`#F4E9ED`)** y **Gris Tanque Inox (`#D9D9D9`)**.

---

## 02 · Webs de referencia
1. **Awwwards Inspiration — "About Us from Faktory":**
   - **URL:** `https://www.awwwards.com/inspiration/about-us-faktory`
   - **Capturas descargadas:** [`referencias/faktory_element_1.png`](file:///E:/WEBS/cerveceria-barcelona/referencias/faktory_element_1.png) y [`referencias/faktory_element_2.png`](file:///E:/WEBS/cerveceria-barcelona/referencias/faktory_element_2.png)
   - **Elementos clave observados:**
     - Cabecera en 3 bloques: Sello técnico izquierdo con borde `#FF6233` (`CONTACTO` + icono lineal de vaso/hamburguesa + email + teléfono), logotipo geométrico central con barra inferior y copa integrada, y botón `MENÚ` gigante a la derecha.
     - Titular gigante apilado a la izquierda (`NUESTROS` / `VALORES`) en `#FF6233` sobre `#0B252F`, acompañado a la derecha por una fotografía vertical bañada en luz ámbar/cobre de una mano alzando un vaso.
     - Manifiesto en caja alta ultra-fina (`Mango Grotesk`) junto a una imagen en arco (`border-radius: 999px`) con palabra clave destacada en `Mango Grotesk Title`.
     - Franja de 3 contadores gigantes (`14 | 28 | 1`) entre líneas horizontales y verticales de `1px solid #FF6233`, flanqueada a la derecha por un retrato cuadrado redondeado con estelas de luz naranja.
2. **Sitio en vivo — `https://faktory.fr/a-propos/`:**
   - **Capturas de scroll:** [`referencias/about_scroll_0.jpg`](file:///E:/WEBS/cerveceria-barcelona/referencias/about_scroll_0.jpg) a [`referencias/about_scroll_9.jpg`](file:///E:/WEBS/cerveceria-barcelona/referencias/about_scroll_9.jpg)
   - **Elementos clave observados:**
     - Cinta diagonal rotada (`-6.5deg`) en color crema `#F4E9ED` con bordes discontinuos naranjas, iconos lineales y marquee gigante `- FÀBRIKA - FÀBRIKA -`.
     - Sección de **Cronología (`CRONOLOGÍA DE UNA AVENTURA CERVECERA DESDE 2012`)** sobre fondo naranja `#FF6233` con texto en burdeos `#780F18`, fotos históricas en blanco y negro y código de barras decorativo.
     - Banda burdeos profunda (`#4D0007`), sección de empleo sobre crema (`#F4E9ED`), sección de contacto sobre gris tanque (`#D9D9D9`) y footer en azul petróleo (`#0B252F`).

---

## 03 · Tipografías (Archivos originales `.ttf` extraídos de la referencia)
1. **`Mango Grotesk Title` (`fonts/Mango-Grotesk-Title.ttf`):**
   - **Rol:** Titulares masivos (`NUESTROS VALORES`, `¿QUÉ ES FÀBRIKA?`), numerales gigantes (`14`, `28`, `1`, `2012`), navegación (`CONTACTO`, `MENÚ`) y cintas marquee.
   - **Peso y estilo:** Display Condensed Heavy Uppercase (`line-height: 0.86`).
2. **`Mango Grotesk` (`fonts/Mango-Grotesk.ttf`):**
   - **Rol:** Manifiesto en caja alta ultra-estilizada, subtítulos de contadores, textos de cronología histórica y listado de oficios cerveceros.
   - **Peso y estilo:** Tall Ultra-Thin Condensed Uppercase (`400`, `line-height: 1.05`).

---

## 04 · Paleta de colores (100% Fiel a Faktory)
| Nombre | Código HEX | Uso en el diseño |
|---|---|---|
| **Petrol Abyss (Fondo Principal)** | `#0B252F` | Fondo del Hero, Manifiesto, Contadores y Footer |
| **Deep Petrol Shadow** | `#02141B` | Sombras profundas, menú desplegable y contrastes oscuros |
| **Burnt Tangerine (Acento & Cronología)** | `#FF6233` | Tipografía principal sobre petróleo y fondo completo de la sección Cronología |
| **Copper Hop (Texto Fino)** | `#FF7657` | Párrafos del manifiesto en `Mango Grotesk` y líneas divisorias |
| **Toasted Malt Burgundy** | `#780F18` / `#4D0007` | Tipografía y líneas sobre el fondo naranja `#FF6233` + sección de grifos/bodega |
| **Foam Cream** | `#F4E9ED` | Fondo de la cinta marquee diagonal y de la sección de Equipo/Candidaturas |
| **Inox Tank Gray** | `#D9D9D9` | Fondo de la sección de Contacto y reservas |

---

## 05 · Componentes, animaciones y efectos
- **Sello de Contacto Superior Izquierdo:** Caja técnica con flecha `←`, correo `HOLA@FABRIKABCN.CAT`, teléfono `93 485 21 09`, texto `CONTACTO` e ilustración SVG lineal de una pinta artesanal y flor de lúpulo.
- **Emblema Central `FÀBRIKA`:** Logotipo SVG a medida donde la letra central dibuja una copa de cerveza artesanal sobre doble barra naranja.
- **Cinta Marquee Diagonal Interactiva:** Banda inclinada con animación continua CSS/JS y doble pista de iconos cerveceros.
- **Cronología Horizontal Interactiva (`2012–2026`):** Navegable mediante scroll o controles de etapa con fotografías de archivo en B&W y códigos de barras técnicos.

---

## 06 · Capturas y archivos visuales
- **Referencias:**
  - [`referencias/faktory_element_1.png`](file:///E:/WEBS/cerveceria-barcelona/referencias/faktory_element_1.png)
  - [`referencias/faktory_element_2.png`](file:///E:/WEBS/cerveceria-barcelona/referencias/faktory_element_2.png)
  - [`referencias/faktory_live_about.png`](file:///E:/WEBS/cerveceria-barcelona/referencias/faktory_live_about.png)
- **Activos propios creados para la cervecería (`assets/brew_*.png`):**
  - `assets/brew_hero_glass.png`: Mano alzando vaso de cerveza artesanal iluminado en tono ámbar/cobre intenso.
  - `assets/brew_arch_hops.png`: Imagen en arco vertical de cocción de malta y fuego/vapor nocturno.
  - `assets/brew_neon_brewer.png`: Retrato cuadrado redondeado con estelas de luz naranja del maestro cervecero.
  - `assets/brew_taproom_wide.png`: Panorámica social de brindis en las mesas largas del taproom de Poblenou.
  - `assets/brew_hop_badge.png`, `assets/brew_vintage_1.png`, `assets/brew_vintage_2.png`, `assets/brew_timeline_1.png`, `assets/brew_timeline_2.png`, `assets/brew_timeline_3.png`: Fotografías en blanco y negro de estética analógica para la cronología `2012–2026`.

---

## 07 · Requisitos e instrucciones
- **Qué hacer:**
  - Mantener exactamente la misma tipografía (`Mango Grotesk Title` + `Mango Grotesk`) y la misma paleta de colores (`#0B252F`, `#FF6233`, `#FF7657`, `#780F18`, `#4D0007`, `#F4E9ED`, `#D9D9D9`).
  - Adaptar todo el contenido, iconografía, cifras, cronología y fotografías a una cervecería artesanal de Barcelona (`FÀBRIKA — El Poblenou, Barcelona`).
  - Sincronizar también con el repositorio de GitHub/Lovable si el usuario lo desea.
