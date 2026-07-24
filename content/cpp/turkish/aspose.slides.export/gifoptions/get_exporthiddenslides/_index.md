---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.
type: docs
weight: 27
url: /tr/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() yöntemi


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Açıklamalar


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ayrıca Bakınız

* Sınıf [GifOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)