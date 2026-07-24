---
title: GetEffective()
second_title: Aspose.Slides for C++ API Referansı
description: Kalıtım uygulanmış etkili metin stili biçimlendirme verilerini alır.
type: docs
weight: 27
url: /tr/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() yöntemi


Kalıtım uygulanmış etkili metin stili biçimlendirme verilerini alır.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Dönüş Değeri

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Açıklamalar



Bu örnek, etkili metin stili özelliklerinden bazılarını almayı gösterir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Sınıf [TextStyle](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)