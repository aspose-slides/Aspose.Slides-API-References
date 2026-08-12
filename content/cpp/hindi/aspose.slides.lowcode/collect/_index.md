---
title: Collect
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Presentation से विभिन्न प्रकार के मॉडल ऑब्जेक्ट्स एकत्र करने के लिए अभिप्रेत विधियों का समूह दर्शाता है।
type: docs
weight: 1
url: /hi/aspose.slides.lowcode/collect/
---
## एकत्रित क्लास


यह [Presentation](../../aspose.slides/presentation/) से विभिन्न प्रकार के मॉडल ऑब्जेक्ट्स एकत्र करने के लिए अभिप्रेत विधियों के समूह का प्रतिनिधित्व करता है।

```cpp
class Collect
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [Presentation](../../aspose.slides/presentation/) में सभी [Shape](../../aspose.slides/shape/) के उदाहरण एकत्र करता है। |
## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... आकार स्वरूपण या अन्य गुण बदलें
}
```

## और देखें

* नामस्थान [Aspose::Slides::LowCode](../)
* लाइब्रेरी [Aspose.Slides](../../)