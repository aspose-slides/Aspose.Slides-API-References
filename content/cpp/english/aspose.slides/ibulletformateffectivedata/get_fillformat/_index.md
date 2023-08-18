---
title: get_FillFormat()
second_title: Aspose.Slides for C++ API Reference
description: Returns the bullet fill format of a paragraph. Read-only IFillFormatEffectiveData.
type: docs
weight: 144
url: /aspose.slides/ibulletformateffectivedata/get_fillformat/
---
## IBulletFormatEffectiveData::get_FillFormat() method


Returns the bullet fill format of a paragraph. Read-only [IFillFormatEffectiveData](../../ifillformateffectivedata/).

```cpp
virtual System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::IBulletFormatEffectiveData::get_FillFormat()=0
```

## Remarks


This example demonstrates retrieving bullet's fill effective data. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"SomePresentation.pptx");
// Assume that the first shape on the first slide is AutoShape with some text...
// Output information about text paragraphs' bullets
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* Class [IBulletFormatEffectiveData](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)