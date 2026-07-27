---
title: RegexOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Opciones de expresiones regulares.
type: docs
weight: 118
url: /es/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum


[Regex](../regex/) opciones.

```cpp
enum class RegexOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Comportamiento predeterminado. |
| Compiled | 1 | Compila la expresión regular para mejorar el rendimiento. Siempre se hace por defecto. |
| CultureInvariant | 2 | Utiliza coincidencia independiente de la cultura. Ignorado. |
| ECMAScript | 4 | Utiliza la sintaxis ECMAScript. Ignorado. |
| ExplicitCapture | 8 | Captura explícita únicamente. Ignorado. |
| IgnoreCase | 16 | Ignora mayúsculas y minúsculas al coincidir. |
| IgnorePatternWhitespace | 32 | Ignora espacios en blanco en el patrón. No compatible. |
| Multiline | 64 | Trata '^' y '$' como inicio y fin de línea, no de la cadena completa. |
| RightToLeft | 128 | Coincidencia de derecha a izquierda. No compatible. |
| Singleline | 256 | Hace que '.' coincida con cualquier carácter sin excepciones (normalmente, los caracteres de nueva línea no se coinciden). |

## Ver también

* Espacio de nombres [System::Text::RegularExpressions](../)
* Biblioteca [Aspose.Slides](../../)