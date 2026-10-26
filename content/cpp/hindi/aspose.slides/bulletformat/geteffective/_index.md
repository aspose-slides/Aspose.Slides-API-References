---
title: GetEffective()
second_title: Aspose.Slides for C++ API संदर्भ
description: विरासत लागू किए गए प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है।
type: docs
weight: 248
url: /hi/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() method


विरासत लागू किए गए प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है।

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### रिटर्न मान

एक [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)।
## टिप्पणी



यह उदाहरण कुछ प्रभावी बुलेट फ़ॉर्मेट गुण प्राप्त करने का प्रदर्शन करता है।
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

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* क्लास [BulletFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)