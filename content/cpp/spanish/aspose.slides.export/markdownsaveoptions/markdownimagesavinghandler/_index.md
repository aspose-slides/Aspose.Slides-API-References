---
title: MarkdownImageSavingHandler
second_title: Referencia API de Aspose.Slides para C++
description: Invocado para cada imagen que no sea SVG (bitmap o metafile) durante la exportación Markdown.  Devuelva true para usar el enlace especificado,  o false para aplicar la lógica de guardado predeterminada.
type: docs
weight: 300
url: /es/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef

Invocado para cada imagen que no sea SVG (bitmap o metafile) durante la exportación de Markdown. 

 Devuelva **true** para usar el *enlace* especificado, 

 o **false** para aplicar la lógica de guardado predeterminada.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```

## Ver también

* Clase [MarkdownSaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)