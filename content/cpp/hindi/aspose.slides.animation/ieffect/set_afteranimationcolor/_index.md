---
title: set_AfterAnimationColor()
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के लिए बाद के एनीमेशन रंग को परिभाषित किया गया। लिखें IColorFormat.
type: docs
weight: 261
url: /hi/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) मेथड

इफ़ेक्ट के लिए बाद के एनिमेशन रंग को परिभाषित किया गया। [IColorFormat](../../../aspose.slides/icolorformat/) लिखें।

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## टिप्पणी

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IColorFormat](../../../aspose.slides/icolorformat/)
* क्लास [IEffect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)