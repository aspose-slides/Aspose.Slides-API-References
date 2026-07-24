---
title: set_AnimateTransitions()
second_title: Aspose.Slides for C++ API Referansı
description: Geçiş animasyonu seçeneğini ayarlar. bool yazın.
type: docs
weight: 14
url: /tr/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) yöntem


Geçiş animasyonu seçeneğini ayarlar. **bool** yazın.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## İlgili

* Sınıf [IHtml5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)