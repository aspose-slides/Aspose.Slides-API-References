---
title: MarkdownSvgImageSavingHandler
second_title: Referencia de la API de Aspose.Slides para C++
description: Invocado para cada imagen SVG durante la exportación de Markdown.  Devuelve true para usar el enlace especificado,  o false para aplicar la lógica de guardado predeterminada.
type: docs
weight: 313
url: /es/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef

Invocado para cada imagen SVG durante la exportación de Markdown.

Devuelve **true** para usar el *enlace* especificado,

o **false** para aplicar la lógica de guardado predeterminada.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```

## Ver también

* Clase [MarkdownSaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)