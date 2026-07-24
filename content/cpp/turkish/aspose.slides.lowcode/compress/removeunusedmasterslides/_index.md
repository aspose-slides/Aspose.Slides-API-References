---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides C++ API Referansı
description: Kullanılmayan ana slaytları kaldırarak Sunumu sıkıştırır.
type: docs
weight: 1
url: /tr/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) metodu


Kullanılmayan ana slaytları kaldırarak [Presentation](../../../aspose.slides/presentation/) sıkıştırmasını yapar.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Sunum örneği |
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [Compress](../)
* İsim Alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)