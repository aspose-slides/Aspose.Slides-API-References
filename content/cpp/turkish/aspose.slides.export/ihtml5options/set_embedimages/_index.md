---
title: set_EmbedImages()
second_title: Aspose.Slides için C++ API Referansı
description: Görsellerin gömme seçeneğini ayarlar. bool yazın.
type: docs
weight: 66
url: /tr/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) method


Görsellerin gömülmesi seçeneğini ayarlar. Yazın **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Ayrıca Bakınız

* Sınıf [IHtml5Options](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)