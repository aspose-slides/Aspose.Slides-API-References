---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API Referansı
description: Görüntü gömme seçeneğini ayarlar. Yaz bool.
type: docs
weight: 66
url: /tr/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metod


Görüntü gömme seçeneğini ayarlar. Yaz **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Diğerlerine Bakın

* Sınıf [Html5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)