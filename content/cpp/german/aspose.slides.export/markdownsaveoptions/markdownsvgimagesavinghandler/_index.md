---
title: MarkdownSvgImageSavingHandler
second_title: Aspose.Slides für C++ API Referenz
description: Wird für jedes SVG image während des Markdown export aufgerufen.  Gibt true zurück, um den angegebenen link ,  oder false, um die Standardspeicherlogik anzuwenden.
type: docs
weight: 313
url: /de/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Wird für jedes SVG-Bild während des Markdown-Exports aufgerufen. 

Gibt **true** zurück, um den angegebenen *link* zu verwenden, 

oder **false**, um die Standardspeicherlogik anzuwenden.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## Siehe auch

* Klasse [MarkdownSaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)