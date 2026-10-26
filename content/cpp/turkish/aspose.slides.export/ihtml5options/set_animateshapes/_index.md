---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API Referansı
description: Şekiller animasyon seçeneğini ayarlar. Bool yazın.
type: docs
weight: 40
url: /tr/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) metodu


Şekiller animasyon seçeneğini ayarlar. **bool** yazın.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Ayrıca Bakınız

* Sınıf [IHtml5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)