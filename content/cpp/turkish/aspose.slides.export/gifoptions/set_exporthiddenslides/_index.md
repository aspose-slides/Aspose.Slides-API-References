---
title: set_ExportHiddenSlides()
second_title: C++ için Aspose.Slides API Referansı
description: Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.
type: docs
weight: 40
url: /tr/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) method


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
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
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)