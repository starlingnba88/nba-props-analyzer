# NBA Props Analyzer V2 — guía de instalación gratuita

## Qué incluye
- Aplicación web estática adaptable a celular y computadora.
- Calculadora de cuotas americanas, probabilidad implícita, edge y EV.
- Comparador manual Apuestas / SuperBets.
- Registro local de análisis y exportación CSV.
- Módulo de conexión opcional a NBA Stat para calendario, jugadores, game logs y lesiones.
- Modelo exploratorio basado en resultados recientes y de temporada; muestra tamaño de muestra y no inventa cuotas.

## Importante sobre datos
NBA Stat requiere una cuenta y un token personal. Consulta https://nbastat.io/developers/api y crea el token desde tu perfil. La documentación indica un límite por defecto de 10 solicitudes autenticadas por hora. El token se guarda solo en la sesión del navegador y no debe compartirse ni subirse a GitHub.

La API es para entretenimiento personal y no constituye asesoramiento financiero/de apuestas. El proveedor advierte que los datos de disponibilidad son estimaciones. La conexión desde el navegador también depende de que el proveedor permita CORS; si el navegador la bloquea, no se debe desactivar la seguridad. Se necesitaría un proxy/backend seguro, que ya no es hosting estático puro.

## Publicar gratis con GitHub Pages
1. Crea una cuenta en https://github.com/signup.
2. Crea un repositorio nuevo llamado `nba-props-analyzer`.
3. Sube `index.html` (y este README si quieres) a la raíz del repositorio.
4. En el repositorio entra a Settings → Pages.
5. En Build and deployment elige `Deploy from a branch`, rama `main`, carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio. La URL será `https://TU-USUARIO.github.io/nba-props-analyzer/`.
7. Abre esa URL en tu Samsung Fold. En Chrome puedes usar menú ⋮ → Añadir a pantalla principal.

No pongas tokens, contraseñas ni claves API dentro del repositorio ni en capturas públicas.
