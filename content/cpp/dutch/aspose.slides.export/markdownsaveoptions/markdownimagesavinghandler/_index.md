---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides voor C++ API-referentie
description: Aangeroepen voor elke niet-SVG-afbeelding (bitmap of metafile) tijdens de Markdown-export.  Retourneer true om de opgegeven link ,  of false om de standaard opslaanlogica toe te passen.
type: docs
weight: 300
url: /nl/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Aangeroepen voor elke niet-SVG-afbeelding (bitmap of metafile) tijdens de Markdown-export. 

 Retourneer **true** om de opgegeven *link* te gebruiken , 

 of **false** om de standaard opslaanlogica toe te passen.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Zie ook

* Klasse [MarkdownSaveOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)