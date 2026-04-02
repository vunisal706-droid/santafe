# Santa Fe Histórica - CEIP Capitulaciones

Guía turística interactiva de los monumentos históricos de Santa Fe, Granada.

## Características

- 🗺️ **Mapa interactivo** con Leaflet
- 📍 **Detección automática** de monumentos cercanos (80m)
- 🧭 **Rutas GPS** óptimas desde tu ubicación
- 🎬 **Videos y audios** subidos por el profesorado
- 🌍 **Multilingüe**: Español, Inglés, Francés, Chino, Árabe
- 📱 **PWA**: Funciona offline como app instalable
- 🔐 **Panel de administración** para gestionar contenidos

## Monumentos incluidos

1. Plaza de España
2. Iglesia Mayor de la Encarnación
3. Arco de Loja
4. Arco de Granada
5. Arco de Jaén
6. Arco Real
7. Centro Damián Bayón

## Cómo usar

1. Abre la app en tu móvil
2. Selecciona una ruta (Completa, Arcos, o Express)
3. Pulsa "Explorar Mapa"
4. Activa el GPS para detección automática
5. Cuando estés cerca de un monumento, la app te avisará

## Panel de administración

- Contraseña: `claustro26`
- Permite añadir videos de YouTube
- Permite añadir audios (iVoox o MP3)
- Permite añadir nuevos monumentos

## Despliegue en GitHub Pages

1. Crea un nuevo repositorio en GitHub
2. Sube todos estos archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `capilogo.png`
   - `README.md`
3. Ve a Settings → Pages
4. Selecciona "Deploy from a branch" → "main"
5. Tu app estará disponible en `https://tuusuario.github.io/nombre-repo`

## Estructura de archivos

```
/
├── index.html      # App principal
├── manifest.json   # Configuración PWA
├── sw.js           # Service Worker (offline)
├── capilogo.png    # Logo del colegio
└── README.md       # Este archivo
```

## Tecnologías

- HTML5 + CSS3 + JavaScript vanilla
- Leaflet.js para mapas
- LocalStorage para guardar datos
- Service Workers para offline

## Créditos

Creado por el **CEIP Capitulaciones de Santa Fe** - Proyecto 24/25
