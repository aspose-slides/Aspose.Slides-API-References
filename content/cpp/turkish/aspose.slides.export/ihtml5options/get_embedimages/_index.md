---
title: get_EmbedImages()
second_title: Aspose.Slides C++ API Referansı
description: Görsellerin gömme seçeneğini döndürür. bool okur.
type: docs
weight: 53
url: /tr/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() metodu


Görsellerin gömme seçeneğini döndürür. **bool** okur.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## İlgili

* Sınıf [IHtml5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)