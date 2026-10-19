# Brochures empresariales

Skill de Codex para crear y actualizar brochures comerciales e institucionales de distintas empresas. Guía la revisión de fuentes, el diseño de una portada propia de la marca, la redacción de servicios y la comprobación del PDF final.

No incluye logos, fotografías, textos comerciales ni datos de contacto de clientes. Cada brochure se construye con la información de la empresa correspondiente.

## Instalación en Codex

En macOS o Linux:

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
git clone https://github.com/soultec-an-fe/brochures-empresariales.git "${CODEX_HOME:-$HOME/.codex}/skills/brochures-empresariales"
```

Para actualizar una instalación hecha con Git:

```bash
git -C "${CODEX_HOME:-$HOME/.codex}/skills/brochures-empresariales" pull
```

También puedes descargar el repositorio y copiar la carpeta `brochures-empresariales` dentro de la carpeta `skills` de Codex.

## Uso

Invócala por nombre en una solicitud a Codex:

```text
Usa $brochures-empresariales para crear un brochure digital de [empresa].
Aquí están el logo, la web, los servicios, el teléfono y las redes sociales.
El público es [público] y quiero destacar [servicios prioritarios].
```

Para comenzar, ayuda compartir el nombre público de la empresa, su logotipo, sitio web o guía de marca, servicios y prioridades, público, formato deseado, teléfono, correo, dirección y enlaces de redes. La skill pide los datos imprescindibles que falten y no inventa cifras ni promesas comerciales.

## Qué revisa

- Portada relacionada con la empresa y sus servicios, sin copiar textos o promociones de una referencia visual.
- Colores, tipografía y jerarquía consistentes entre portada e interiores.
- Iconos proporcionados y enlaces correctos para redes sociales, WhatsApp, sitio web y ubicación.
- Número visible separado del formato internacional del enlace de WhatsApp.
- Páginas renderizadas, enlaces interactivos y QR leídos desde el PDF exportado.

Las instrucciones principales están en [`SKILL.md`](SKILL.md). La revisión detallada del PDF está en [`references/revision-pdf.md`](references/revision-pdf.md).

## Licencia

MIT. Consulta [`LICENSE`](LICENSE).
