---
title: set_Rewind()
second_title: مرجع API Aspose.Slides برای C++
description: این ویژگی مشخص می‌کند که آیا اثر پس از اتمام پخش دوباره باز می‌گردد یا نه. نوشتن bool.
type: docs
weight: 248
url: /fa/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) متد

این ویژگی مشخص می‌کند که آیا اثر پس از پایان پخش دوباره باز می‌گردد یا نه. نوشتن **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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

## موارد مرتبط

* کلاس [Timing](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)