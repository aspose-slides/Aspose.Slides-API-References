---
title: get_FillFormat()
second_title: Aspose.Slides için C++ API Referansı
description: Bir paragrafın madde işareti doldurma biçimini döndürür. Salt-okunur IFillFormatEffectiveData.
type: docs
weight: 131
url: /tr/aspose.slides/ibulletformateffectivedata/get_fillformat/
---
## IBulletFormatEffectiveData::get_FillFormat() yöntem


Bir paragrafın madde işareti doldurma biçimini döndürür. Salt-okunur [IFillFormatEffectiveData](../../ifillformateffectivedata/).

```cpp
virtual System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::IBulletFormatEffectiveData::get_FillFormat()=0
```

## Açıklamalar


Bu örnek, madde işaretinin doldurma etkili verisinin alınmasını gösterir. 
 ```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"SomePresentation.pptx");
// İlk slayttaki ilk şeklin, bazı metin içeren bir AutoShape olduğunu varsayın...
// Metin paragraflarının madde işaretleri hakkında bilgi yazdır
auto autoShape = ExplicitCast<Aspose::Slides::AutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
for (auto para : IterateOver(autoShape->get_TextFrame()->get_Paragraphs()))
{
    auto bulletFormatEffective = para->get_ParagraphFormat()->get_Bullet()->GetEffective();
    Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(bulletFormatEffective->get_Type()));
    if (bulletFormatEffective->get_Type() != Aspose::Slides::BulletType::None)
    {
        Console::WriteLine(String(u"Bullet fill type: ") + ObjectExt::ToString(bulletFormatEffective->get_FillFormat()->get_FillType()));
        switch (bulletFormatEffective->get_FillFormat()->get_FillType())
        {
            case Aspose::Slides::FillType::Solid:
                Console::WriteLine(String(u"Solid fill color: ") + bulletFormatEffective->get_FillFormat()->get_SolidFillColor());
                break;

            case Aspose::Slides::FillType::Gradient:
            {
                Console::WriteLine(String(u"Gradient stops count: ") + bulletFormatEffective->get_FillFormat()->get_GradientFormat()->get_GradientStops()->get_Count());
                for (auto gradStop : IterateOver(bulletFormatEffective->get_FillFormat()->get_GradientFormat()->get_GradientStops()))
                {
                    Console::WriteLine(Convert::ToString(gradStop->get_Position()) + u": " + gradStop->get_Color());
                }
                break;
            }

            case Aspose::Slides::FillType::Pattern:
                Console::WriteLine(String(u"Pattern style: ") + ObjectExt::ToString(bulletFormatEffective->get_FillFormat()->get_PatternFormat()->get_PatternStyle()));
                Console::WriteLine(String(u"Fore color: ") + bulletFormatEffective->get_FillFormat()->get_PatternFormat()->get_ForeColor());
                Console::WriteLine(String(u"Back color: ") + bulletFormatEffective->get_FillFormat()->get_PatternFormat()->get_BackColor());
                break;

            default:
                break;
        }
    }
    Console::WriteLine();
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* Sınıf [IBulletFormatEffectiveData](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)