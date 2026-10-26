---
title: MarkdownSvgImageSavingHandler
second_title: Riferimento API Aspose.Slides per C++
description: Invocato per ogni immagine SVG durante l'esportazione Markdown. Restituisce true per utilizzare il link specificato, oppure false per applicare la logica di salvataggio predefinita.
type: docs
weight: 313
url: /it/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Invocato per ogni immagine SVG durante l'esportazione Markdown. 

 Restituisce **true** per utilizzare il *link* specificato, 

 oppure **false** per applicare la logica di salvataggio predefinita.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## Vedi anche

* Classe [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)