---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides för C++ API-referens
description: Anropas för varje icke-SVG-bild (bitmap eller metafile) under Markdown-export. Return true för att använda den angivna länken, eller false för att tillämpa standard sparlogik.
type: docs
weight: 300
url: /sv/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Anropas för varje icke-SVG-bild (bitmap eller metafil) under Markdown-export. 

 Return **true** för att använda den angivna *länken* , 

 eller **false** för att använda standard-sparlogik.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Se även

* Klass [MarkdownSaveOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)