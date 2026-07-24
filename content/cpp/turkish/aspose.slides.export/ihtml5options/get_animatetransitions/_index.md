---
title: get_AnimateTransitions()
second_title: Aspose.Slides için C++ API Referansı
description: Geçiş animasyonu seçeneğini döndürür. Okunur bool.
type: docs
weight: 1
url: /tr/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() metod


Geçiş animasyonu seçeneğini döndürür. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Ayrıca Bakınız

* Sınıf [IHtml5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)