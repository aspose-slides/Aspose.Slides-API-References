---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides pro C++ API Reference
description: Voláno pro každý ne-SVG obrázek (bitmapu nebo metafil) během exportu Markdown. Vrátí true, pokud chcete použít určený odkaz, nebo false, pokud chcete použít výchozí logiku ukládání.
type: docs
weight: 300
url: /cs/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Voláno pro každý ne-SVG obrázek (bitmapu nebo metafil) během exportu Markdown. 

 Vrátí **true**, pokud chcete použít určený *link* , 

 nebo **false**, pokud chcete použít výchozí logiku ukládání.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Viz také

* Třída [MarkdownSaveOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)