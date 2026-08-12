---
title: GetEffective()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: विरासत लागू किए गए प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 248
url: /hi/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() मेथड

विरासत लागू किए गए प्रभावी बुलेट फ़ॉर्मेटिंग डेटा को प्राप्त करता है।

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### रिटर्न मान

A [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## टिप्पणियाँ



यह उदाहरण कुछ प्रभावी बुलेट फ़ॉर्मेट गुणों को प्राप्त करने का प्रदर्शन करता है। 
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

## साथ ही देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Class [IBulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)