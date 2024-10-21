# Introducción a Markdown

**Markdown** es un lenguaje de marcado ligero utilizado principalmente para formatear texto de una manera sencilla que puede ser interpretada fácilmente en HTML o en otros formatos. Fue creado por John Gruber en 2004 con el objetivo de ser fácil de escribir y leer, incluso en su forma no procesada. Es ampliamente utilizado en la documentación de software, redacción de artículos y en plataformas de desarrollo colaborativo como GitHub, donde permite formatear archivos README, issues, comentarios, entre otros.

## Lo más básico de Markdown

### 1. Encabezados
Para crear encabezados, se utiliza el símbolo de almohadilla `#`. Cuantas más almohadillas uses, más bajo será el nivel del encabezado.
- `# Encabezado 1` 
- `## Encabezado 2`
- `### Encabezado 3`

Ejemplo:
```markdown
# Título Principal
## Subtítulo
### Sub-subtítulo
```

### 2. Texto en negrita y cursiva:
- Para **negrita**, se encierra el texto con dos asteriscos o guiones bajos.
  - `**negrita**` o `__negrita__`
- Para *cursiva*, se usa un asterisco o guion bajo.
  - `*cursiva*` o `_cursiva_`
- También se puede combinar: `***negrita y cursiva***`.

Ejemplo:
```markdown
Este es un texto en **negrita** y este en *cursiva*.
```

### 3. Listas:
- **Listas no ordenadas**: Se crean usando `*`, `+` o `-` seguido de un espacio.
  ```markdown
  * Elemento 1
  * Elemento 2
  ```
- **Listas ordenadas**: Se utilizan números seguidos de un punto.
  ```markdown
  1. Primer elemento
  2. Segundo elemento
  ```

### 4. Enlaces:
Se crean colocando el texto entre corchetes `[ ]` seguido de la URL entre paréntesis `( )`.
```markdown
[Enlace a Google](https://www.google.com)
```

### 5. Imágenes:
Se usa una sintaxis similar a los enlaces, pero con un signo de exclamación `!` antes.
```markdown
![Texto alternativo](URL-de-la-imagen)
```

### 6. Citas:
Se indica una cita con el símbolo `>`.
```markdown
> Esto es una cita.
```

### 7. Código:
- Para fragmentos cortos de código dentro de una línea de texto, usa comillas invertidas `` ` ``.
  ```markdown
  `Este es un código en línea.`
  ```
- Para bloques de código, usa tres comillas invertidas `` ``` ``.
  ```markdown
  ```
  Código de ejemplo
  ```
  ```

### 8. Tablas:
Se crean usando `|` para separar las columnas y `-` para crear las líneas de la cabecera.
```markdown
| Columna 1 | Columna 2 |
|-----------|-----------|
| Valor 1   | Valor 2   |
```

## Ejemplo simple de Markdown

```markdown
# Mi Proyecto

Este es un **resumen** del proyecto.

## Características

* Fácil de usar
* Flexible
* Documentación extensa

## Enlaces útiles

[Visitar GitHub](https://github.com)
```

## Usos de Markdown
- **Documentación técnica**: En GitHub, GitLab y Bitbucket, es común usar archivos README.md para documentar proyectos.
- **Publicación de blogs**: Muchas plataformas de blogging como Jekyll y Ghost utilizan Markdown.
- **Notas personales**: Herramientas como Obsidian y Notion permiten escribir notas con Markdown.

Markdown es simple y rápido de aprender, pero también lo suficientemente poderoso para producir documentación clara y estructurada.