---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.
type: docs
weight: 40
url: /tr/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) metodu


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ayrıca Bakınız

* Sınıf [IGifOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)