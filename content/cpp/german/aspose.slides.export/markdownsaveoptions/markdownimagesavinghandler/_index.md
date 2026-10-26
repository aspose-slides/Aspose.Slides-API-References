---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides für C++ API-Referenz
description: Für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports aufgerufen. Gibt true zurück, um den angegebenen link zu verwenden, oder false, um die Standardspeicherlogik anzuwenden.
type: docs
weight: 300
url: /de/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Wird für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports aufgerufen. 

 Gibt **true** zurück, um den angegebenen *link* , 

 oder **false** um die Standard-Speicherlogik anzuwenden.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Siehe auch

* Klasse [MarkdownSaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)