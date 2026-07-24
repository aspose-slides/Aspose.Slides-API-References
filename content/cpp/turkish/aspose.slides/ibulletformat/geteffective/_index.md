---
title: GetEffective()
second_title: Aspose.Slides için C++ API Referansı
description: Kalıtım uygulanmış etkili madde işareti biçimlendirme verilerini alır.
type: docs
weight: 248
url: /tr/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() yöntemi


Kalıtım uygulanmış etkili madde işaretleme biçimlendirme verilerini alır.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### Dönüş Değeri

Bir [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Açıklamalar



Bu örnek, bazı etkili madde işareti biçim özelliklerini almayı gösterir. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Sınıf [IBulletFormat](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)