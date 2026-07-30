---
title: MarkdownImageSavingHandler
second_title: Riferimento API di Aspose.Slides per C++
description: Invocata per ogni immagine non SVG (bitmap o metafile) durante l'esportazione Markdown.  Restituisce true per utilizzare il collegamento specificato, oppure false per applicare la logica di salvataggio predefinita.
type: docs
weight: 300
url: /it/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Invocata per ogni immagine non SVG (bitmap o metafile) durante l'esportazione Markdown. 

 Return **true** per utilizzare il *link* , 

 oppure **false** per applicare la logica di salvataggio predefinita.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Vedi anche

* Classe [MarkdownSaveOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)