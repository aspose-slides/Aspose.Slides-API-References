---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides dla C++ referencja API
description: Wywoływany dla każdego obrazu nie-SVG (bitmapa lub metafile) podczas eksportu do Markdown. Zwróć true, aby użyć określonego odnośnika, lub false, aby zastosować domyślną logikę zapisywania.
type: docs
weight: 300
url: /pl/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Wywoływany dla każdego obrazu nie-SVG (bitmapa lub metafile) podczas eksportu do Markdown. 

 Return **true**, aby użyć określonego *odnośnika* , 

 or **false**, aby zastosować domyślną logikę zapisywania.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Zobacz także

* Klasa [MarkdownSaveOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)