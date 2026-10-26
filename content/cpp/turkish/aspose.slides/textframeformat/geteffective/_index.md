---
title: GetEffective()
second_title: Aspose.Slides için C++ API Referansı
description: Miras uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır.
type: docs
weight: 391
url: /tr/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() yöntemi


Miras uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### Dönüş Değeri

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## Açıklamalar



Bu örnek, etkili metin çerçevesi biçimlendirme özelliklerinden bazılarının alınmasını göstermektedir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Sınıf [TextFrameFormat](../)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)