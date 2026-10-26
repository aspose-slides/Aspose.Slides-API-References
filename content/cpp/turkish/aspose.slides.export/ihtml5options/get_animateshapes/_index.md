---
title: get_AnimateShapes()
second_title: Aspose.Slides için C++ API Referansı
description: Şekillerin animasyon seçeneğini döndürür. bool okunur.
type: docs
weight: 27
url: /tr/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() yöntemi


Şekil animasyonu seçeneğini döndürür. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
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