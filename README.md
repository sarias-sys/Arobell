# Propuesta Flow — Laboratorios Arobell

Propuesta comercial interactiva de **Flow × DesarrollAndo** para Laboratorios Arobell.

Un solo archivo (`index.html`), sin dependencias ni build. El logo y el favicon van
incrustados en el archivo, así que funciona igual abierto localmente o publicado.

## Publicar en GitHub Pages

1. Subir `index.html`, `.nojekyll` y este `README.md` a la raíz del repositorio.
2. Entrar a **Settings → Pages**.
3. En *Source* elegir **Deploy from a branch**.
4. Rama `main`, carpeta `/ (root)`. Guardar.
5. En uno o dos minutos queda publicada en:

```
https://sarias-sys.github.io/Aerobell/
```

El archivo `.nojekyll` evita que GitHub procese el sitio con Jekyll. No es
estrictamente necesario aquí, pero previene problemas si más adelante se agregan
carpetas que empiecen por guion bajo.

## Antes de compartir el enlace

- [ ] Reemplazar el correo del botón «Confirmar el arranque» (hoy `comercial@desarrollandoando.com`).
- [ ] Reemplazar los datos del simulador de chat por referencias y precios reales de Arobell.
- [ ] Revisar la fecha y la vigencia de la propuesta al pie de la página.

## Qué es interactivo

| Sección | Interacción |
|---|---|
| Inicio | Simulador del asistente con conversación ramificada que cierra pedido |
| Lo que vimos | Barra de cobertura editable según el horario de atención |
| Campañas | Filtro por cartera, recompra, rescate y servicio |
| Inversión | Calculadora de conversaciones al mes |
| Arrancamos | Checklist con barra de progreso |

## Privacidad

La página lleva `noindex, nofollow` para que no aparezca en buscadores. Aun así, un
repositorio público hace visible el contenido a cualquiera que tenga el enlace. Si la
propuesta debe ser confidencial, conviene un repositorio privado con Pages en un plan
que lo permita, o publicarla bajo un dominio propio con acceso restringido.
