# Skills de Eduardo

6 skills personales en formato `SKILL.md` (frontmatter con `name` y `description`).
Compatibles con **Muse (Meta)**, **Hermes Agent**, **Claude Code / Claude Skills** y cualquier agente que lea carpetas `SKILL.md`.

## Contenido

| Skill | Para qué sirve |
|---|---|
| `optimizador-prompts` | Convierte ideas desordenadas o dictadas por voz en prompts claros y estructurados |
| `entrevistador-procesos` | Define un proceso o automatización con pocas preguntas antes de construirlo |
| `superpowers` | Modo de trabajo riguroso para proyectos con varias partes (entender → planificar → ejecutar → revisar) |
| `presentaciones-visuales` | Convierte cualquier contenido en diapositivas HTML listas para exponer |
| `verificador-datos` | Comprueba datos, cifras, precios y afirmaciones antes de publicarlos |
| `humanizador` | Reescribe textos de IA para que suenen naturales y humanos |

## Instalación en Muse (Meta)

Pega esto en el chat de Muse:

```
mkdir -p ~/workspace/skills && curl -L https://raw.githubusercontent.com/otamendez11/muse-skills/main/skills-para-muse.tar.gz | tar -xz -C ~/workspace/skills && ls -1 ~/workspace/skills
```

Deben aparecer las 6 carpetas. Muse indexa la `description` de cada skill, así que a partir de ahí las encontrará solo.

## Instalación en Hermes Agent

Copia las carpetas a `$HERMES_HOME/skills/personal/` (en Windows: `%LOCALAPPDATA%\hermes\skills\personal\`).

## Archivos

- `skills-para-muse.tar.gz` — paquete para Muse (curl + tar)
- `skills-para-muse.zip` — el mismo paquete en ZIP, por si se prefiere subir un archivo
- `<skill>/SKILL.md` — cada skill suelta
