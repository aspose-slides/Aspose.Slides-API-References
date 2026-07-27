---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides para C++ Referencia de API
description: Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.
type: docs
weight: 235
url: /es/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const método


Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Observaciones


Esta propiedad define si los espacios consecutivos son:
* preservados como caracteres de espacio regular,
* alternados entre espacios regulares y entidades de espacio no separable (**&nbsp;**),
* o totalmente reemplazados (después del primero) con **&nbsp;** para preservar la alineación visual en la salida Markdown.



El valor predeterminado es [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Ver también

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Clase [MarkdownSaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)