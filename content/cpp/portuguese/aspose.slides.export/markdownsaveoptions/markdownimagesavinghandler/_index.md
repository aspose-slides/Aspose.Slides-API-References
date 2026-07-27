---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides para C++ Referência da API
description: Invocado para cada imagem não SVG (bitmap ou metafile) durante a exportação Markdown.  Retorne true para usar o link especificado ,  ou false para aplicar a lógica padrão de salvamento.
type: docs
weight: 300
url: /pt/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Invocado para cada imagem não SVG (bitmap ou metafile) durante a exportação Markdown. 

 Retorne **true** para usar o *link* , 

 ou **false** para aplicar a lógica padrão de salvamento.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Veja Também

* Classe [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)