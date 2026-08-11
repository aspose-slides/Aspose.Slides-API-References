---
title: set_Rewind()
second_title: مرجع API Aspose.Slides برای C++
description: این ویژگی تعیین می‌کند که آیا اثر پس از اتمام پخش، دوباره پخش شود. نوشتن bool.
type: docs
weight: 326
url: /fa/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) متد

این ویژگی تعیین می‌کند که آیا اثر پس از اتمام پخش، دوباره پخش می‌شود یا نه. نوشتن **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

## همچنین ببینید

* کلاس [ITiming](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)