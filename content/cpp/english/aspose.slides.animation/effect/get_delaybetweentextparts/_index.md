---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API Reference
description: Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read float.
type: docs
weight: 300
url: /aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() method


Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## See Also

* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)