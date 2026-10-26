---
title: GetEffective()
second_title: Aspose.Slides için C++ API Referansı
description: Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır.
type: docs
weight: 365
url: /tr/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metodu

Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### Dönüş Değeri

Bir [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Açıklamalar



Bu örnek, bazı etkili paragraf biçim özelliklerinin alınmasını gösterir. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Sınıf [ParagraphFormat](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)