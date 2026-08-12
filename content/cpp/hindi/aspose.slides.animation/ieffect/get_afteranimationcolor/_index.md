---
title: get_AfterAnimationColor()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इफ़ेक्ट के लिए एक बाद-एनीमेशन रंग निर्धारित किया गया है। IColorFormat पढ़ें।
type: docs
weight: 248
url: /hi/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() विधि

प्रभाव के लिए एक बाद-एनीमेशन रंग परिभाषित किया गया है। पढ़ें [IColorFormat](../../../aspose.slides/icolorformat/)।

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IColorFormat](../../../aspose.slides/icolorformat/)
* क्लास [IEffect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)