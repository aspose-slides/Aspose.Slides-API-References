---
title: MarkdownSvgImageSavingHandler
second_title: Referência da API Aspose.Slides para C++
description: Invocado para cada imagem SVG durante a exportação Markdown. Retorne true para usar o link especificado, ou false para aplicar a lógica padrão de salvamento.
type: docs
weight: 313
url: /pt/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Invocado para cada imagem SVG durante a exportação Markdown. 

 Retorne **true** para usar o *link* especificado, 

 ou **false** para aplicar a lógica padrão de salvamento.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## Veja Também

* Classe [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)