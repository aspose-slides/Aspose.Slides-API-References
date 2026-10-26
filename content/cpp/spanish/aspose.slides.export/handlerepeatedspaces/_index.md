---
title: HandleRepeatedSpaces
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.
type: docs
weight: 937
url: /es/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Todos los espacios se conservan como caracteres de espacio regular sin ningún cambio. No se aplica ninguna transformación, y los espacios consecutivos múltiples se exportan tal cual. |
| AlternateSpacesToNbsp | 1 | Convierte secuencias de dos o más espacios regulares consecutivos alternando entre caracteres de espacio regular y entidades de espacio de no separación (**&nbsp;**). El primer espacio siempre se conserva como espacio regular. |
| MultipleSpacesToNbsp | 2 | Convierte secuencias de dos o más espacios regulares consecutivos conservando el primer espacio como carácter de espacio regular y reemplazando todos los espacios subsecuentes por entidades de espacio de no separación (**&nbsp;**). |

## Ver también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)