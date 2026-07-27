---
title: set_HandleRepeatedSpaces()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.
type: docs
weight: 248
url: /es/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) método

Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Observaciones

* preservados como caracteres de espacio regular,
* alternados entre espacios regulares y entidades de espacio no divisible (**&nbsp;**),
* o completamente reemplazados (después del primero) con **&nbsp;** para preservar la alineación visual en la salida Markdown.

El valor predeterminado es [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Ver también

* Enumeración [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Clase [MarkdownSaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)