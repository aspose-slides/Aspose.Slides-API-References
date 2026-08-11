---
title: get_AfterAnimationType()
second_title: مرجع API Aspose.Slides برای C++
description: یک نوع انیمیشن پس از اثر برای افکت تعریف می‌شود. AfterAnimationType را بخوانید.
type: docs
weight: 222
url: /fa/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() متد


نوع انیمیشن پس از اثر تعریف می‌شود. بخوانید [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین افکت از اولین اسلاید.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// تغییر افکت After animation به "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## موارد مرتبط

* Enum [AfterAnimationType](../../afteranimationtype/)
* کلاس [IEffect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)