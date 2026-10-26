---
title: set_AfterAnimationColor()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इफ़ेक्ट के लिए बाद के एनीमेशन रंग को परिभाषित करता है। IColorFormat लिखें।
type: docs
weight: 261
url: /hi/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) विधि

इफ़ेक्ट के लिए बाद के एनीमेशन रंग को परिभाषित करता है। [IColorFormat](../../../aspose.slides/icolorformat/) लिखें।

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// इफ़ेक्ट के After animation प्रकार को "Color" में बदलें।
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// इफ़ेक्ट के After animation रंग को सेट करें।
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IColorFormat](../../../aspose.slides/icolorformat/)
* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)