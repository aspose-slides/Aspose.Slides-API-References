---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API Referansı
description: Geçiş animasyonu seçeneğini döndürür. Okunur bool.
type: docs
weight: 1
url: /tr/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() method

Geçiş animasyonu seçeneğini döndürür. Okunur **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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

* Sınıf [Html5Options](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)