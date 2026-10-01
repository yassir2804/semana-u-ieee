# Agenda · Semana Universitaria IEEE UNA

Página interactiva con la agenda de la Semana U (5–9 oct. 2026): filtro por día, detalle de cada actividad y botón para agregarla a Google Calendar. Es HTML estático (`index.html` + `assets/`), sin build.

## Publicar gratis

**Vercel:** vercel.com → Add New → Project → importar `semana-u-ieee` → Framework: *Other* → Deploy.

**GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → elegir la rama y la carpeta `/ (root)` → Save.

## Editar actividades

Los eventos están en el arreglo `EVENTS` dentro de `index.html` (día, título, hora de inicio/fin en formato 24 h, color e ícono). El lugar aparece como `[Lugar por confirmar]` en el elemento `#d-place`.
