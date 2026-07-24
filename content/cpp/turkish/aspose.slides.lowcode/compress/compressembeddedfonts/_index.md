---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides for C++ API Referansı
description: Gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak Presentation'ın sıkıştırılmasını gerçekleştirir.
type: docs
weight: 27
url: /tr/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) yöntemi

Gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak [Presentation](../../../aspose.slides/presentation/) sıkıştırmasını gerçekleştirir.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Sunum örneği |
## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [Compress](../)
* İsim Uzayı [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)