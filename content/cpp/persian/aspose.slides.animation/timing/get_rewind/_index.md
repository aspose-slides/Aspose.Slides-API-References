---
title: get_Rewind()
second_title: مرجع API Aspose.Slides برای C++
description: این خصوصیت مشخص می‌کند که آیا اثر پس از پایان پخش به عقب باز می‌گردد یا خیر. مقدار بازگشتی bool است.
type: docs
weight: 235
url: /fa/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() متد

This attribute specifies if the effect will rewind when done playing. Read **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## مراجع

* کلاس [Timing](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)