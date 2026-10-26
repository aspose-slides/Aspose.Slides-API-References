---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides for C++ API Referansı
description: Markdown dışa aktarımı sırasında her bir non-SVG görüntü (bitmap veya metafile) için çağrılır. Belirtilen linki kullanmak için true döndürün, veya varsayılan kaydetme mantığını uygulamak için false döndürün.
type: docs
weight: 300
url: /tr/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef

Markdown dışa aktarımı sırasında her bir non-SVG görüntü (bitmap veya metafile) için çağrılır.  

Belirtilen *link*'i kullanmak için **true** döndürün,  

veya varsayılan kaydetme mantığını uygulamak için **false** döndürün.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```

## İlgili

* Sınıf [MarkdownSaveOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)