---
title: get_FillFormat()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक पैराग्राफ़ की बुलेट फ़िल फ़ॉर्मेट को लौटाता है। केवल-पढ़ने योग्य IFillFormatEffectiveData.
type: docs
weight: 131
url: /hi/aspose.slides/ibulletformateffectivedata/get_fillformat/
---
## IBulletFormatEffectiveData::get_FillFormat() विधि


एक पैराग्राफ़ की बुलेट फिल फ़ॉर्मेट को लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../../ifillformateffectivedata/).

```cpp
virtual System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::IBulletFormatEffectiveData::get_FillFormat()=0
```

## टिप्पणियाँ


यह उदाहरण बुलेट के फ़िल प्रभावी डेटा को पुनः प्राप्त करने का प्रदर्शन करता है। 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"SomePresentation.pptx");
// मान लीजिए कि पहली स्लाइड पर पहला आकार AutoShape है जिसमें कुछ टेक्स्ट है...
// टेक्स्ट पैराग्राफ़ों के बुलेट्स की जानकारी आउटपुट करें
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

## संबंधित

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* क्लास [IBulletFormatEffectiveData](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)