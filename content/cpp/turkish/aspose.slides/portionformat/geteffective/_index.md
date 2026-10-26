---
title: GetEffective()
second_title: Aspose.Slides for C++ API Referansı
description: Kalıtım uygulanmış etkili bölüm biçimlendirme verilerini alır.
type: docs
weight: 131
url: /tr/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metodu

Uygulanan kalıtımla birlikte etkili bölüm biçimlendirme verilerini alır.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### Dönüş Değeri

A [IPortionFormatEffectiveData](../../iportionformateffectivedata/).

## Açıklamalar

Bu örnek, bazı etkili bölüm formatı özelliklerinin nasıl alınacağını gösterir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Sınıf [PortionFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)