---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API Reference
description: Defined an after animation type for effect. Read AfterAnimationType.
type: docs
weight: 222
url: /cpp/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() method


Defined an after animation type for effect. Read [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## See Also

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)