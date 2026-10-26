---
title: set_AnimateTransitions()
second_title: Aspose.Slides için C++ API Referansı
description: Geçiş animasyonu seçeneğini ayarlar. Bool yazın.
type: docs
weight: 14
url: /tr/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) metot


Geçiş animasyonu seçeneğini ayarlar. **bool** yazın.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
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
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)