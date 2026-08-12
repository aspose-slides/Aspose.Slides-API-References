---
title: get_AfterAnimationColor()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रभाव के लिए बाद के एनीमेशन का रंग निर्धारित करता है। पढ़ें IColorFormat.
type: docs
weight: 248
url: /hi/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() विधि


इफ़ेक्ट के लिए बाद के एनीमेशन रंग को परिभाषित करता है। पढ़ें [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorFormat](../../../aspose.slides/icolorformat/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)