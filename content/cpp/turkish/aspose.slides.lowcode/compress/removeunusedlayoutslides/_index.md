---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Kullanılmayan yerleşim slaytlarını kaldırarak Sunumu sıkıştırır.
type: docs
weight: 14
url: /tr/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metod

[Presentation](../../../aspose.slides/presentation/)'nin sıkıştırmasını kullanılmayan yerleşim slaytlarını kaldırarak gerçekleştirir.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Sunum örneği |
## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [Compress](../)
* AdAlanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)