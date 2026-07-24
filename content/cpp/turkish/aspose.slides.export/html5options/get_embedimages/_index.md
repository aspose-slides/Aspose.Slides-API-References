---
title: get_EmbedImages()
second_title: Aspose.Slides için C++ API Referansı
description: Görüntü yerleştirme seçeneğini döndürür. Bool okur.
type: docs
weight: 53
url: /tr/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metodu

Görüntü yerleştirme seçeneğini döndürür. Okunur **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Bakınız

* Sınıf [Html5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)