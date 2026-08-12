---
title: get_InkEffect()
second_title: Aspose.Slides for C++ API संदर्भ
description: "इंक इफ़ेक्ट प्रकार (उदा., Galaxy, Gold, Silver) प्राप्त करता है जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। मान ब्रश प्रॉपर्टी \"inkEffects\" से पार्स किया जाता है। यदि कोई मान्यता प्राप्त इफ़ेक्ट निर्दिष्ट नहीं किया गया है, तो InkEffectType::NotDefined लौटाया जाता है।"
type: docs
weight: 53
url: /hi/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() मेथड

इंक इफ़ेक्ट प्रकार (जैसे, Galaxy, Gold, Silver) प्राप्त करता है जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। मान ब्रश प्रॉपर्टी \"inkEffects\" से पार्स किया जाता है। यदि कोई मान्यता प्राप्त इफ़ेक्ट निर्दिष्ट नहीं किया गया है, तो [InkEffectType::NotDefined](../../inkeffecttype/) लौटाया जाता है।

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## संबंधित देखें

* एन्यूम [InkEffectType](../../inkeffecttype/)
* क्लास [IInkBrush](../)
* नेमस्पेस [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)