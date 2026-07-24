[README.md](https://github.com/user-attachments/files/30332721/README.md)
# Kit de comunicación interna

Cinco herramientas web interactivas para un curso de **comunicación interna** en comunidades. Cada una es autónoma (un solo archivo HTML, sin instalar nada), funciona proyectada en grupo o en el móvil de cada participante mediante un **código QR**, y comparten la misma identidad visual.

**▶ Portada del kit:** https://xiskya.github.io/kit/

Desde ahí se abre cualquier herramienta, se escanea su QR o se descarga el kit en PDF. Un único **QR maestro** (`qr-kit-maestro.png`) lleva a esa portada: con un solo código se accede a todo.

## Las cinco herramientas

| # | Herramienta | Para qué sirve | Enlace |
|---|---|---|---|
| 1 | **Termómetro de nuestra escucha** | Autoevaluación de la escucha, personal y comunitaria. Da una «temperatura» y una lectura para crecer. | https://xiskya.github.io/termometro/ |
| 2 | **Genera o rompe la confianza** | Ante situaciones de la vida comunitaria, distingue qué formas de comunicar construyen confianza y cuáles la erosionan. | https://xiskya.github.io/generador/ |
| 3 | **Semáforo de canales** | Diagnostica y reordena los canales: qué se usa, para qué, dónde se pierde la información. | https://xiskya.github.io/semaforo/ |
| 4 | **Un mensaje, tres versiones** | Adivina a quién va dirigida cada versión de una noticia sensible, analiza qué cambia (lenguaje, canal, ritmo, ejemplos, explicación) y escribe la tuya. | https://xiskya.github.io/mensajes/ |
| 5 | **Contrato para la comunicación** | Cierre: cada persona elige dos compromisos, escribe un tercero suyo y genera su contrato personal para firmar y revisar. | https://xiskya.github.io/contrato/ |

## Y además · Resetear la mirada

Una actividad complementaria, fuera del recorrido: para que hermanas que ya conviven **vuelvan a mirarse con ojos nuevos**. Cada una escribe tres «miradas» para tres hermanas concretas y se las entrega en persona o por WhatsApp.

**▶** https://xiskya.github.io/reseteando/

## El recorrido del curso

Las cinco están pensadas para encadenarse:

1. **Termómetro de nuestra escucha** — mirar cómo escucho hoy. El punto de partida.
2. **Genera o rompe la confianza** — ver qué comunicación construye confianza.
3. **Semáforo de canales** — ordenar el desorden de canales.
4. **Un mensaje, tres versiones** — aprender a comunicar lo difícil según a quién.
5. **Contrato para la comunicación** — comprometerse con tres pasos concretos, uno escrito por ella misma. El cierre.

Cada una puede vivirse **en grupo** (proyectada, con debate) o **en individual** (cada participante en su dispositivo).

## Qué contiene este repositorio

Este repo es la **portada del kit**. Incluye:

- `index.html` — la página-portada, con enlace y QR de cada herramienta y un botón para descargar el PDF.
- `kit-comunicacion-interna.pdf` — folleto del kit (A4, con los QR) para imprimir y repartir. *El botón de descarga de la portada espera este archivo en la misma carpeta.*
- `qr-kit-maestro.png` · `.svg` — QR maestro que lleva a esta portada.
- `qr-termometro`, `qr-confianza`, `qr-semaforo`, `qr-mensajes`, `qr-contrato`, `qr-reseteando` (`.png` y `.svg`) — QR de cada herramienta y de la actividad complementaria.
- `README.md` — este archivo.

Las herramientas en sí viven cada una en **su propio repositorio** (`termometro`, `generador`, `semaforo`, `mensajes`, `contrato`, y `reseteando` para la actividad complementaria), con su propio README y sus opciones de personalización.

## Cómo funciona

- **Autónomas:** cada herramienta es un único archivo HTML. Basta abrirlo en el navegador o publicarlo en cualquier hosting estático (GitHub Pages, Netlify, WordPress…).
- **Sin datos:** ninguna guarda ni envía nada. Todo ocurre en el navegador; al recargar, la información desaparece. Lo que se quiere conservar (una lectura, un contrato) se guarda con *Imprimir / Guardar PDF*.
- **Editables:** el contenido de cada una se puede adaptar o traducir. Los detalles están en el README de cada herramienta.

## Uso

Libre para formación. Adáptalo, tradúcelo o intégralo en tus materiales según lo necesites.
