---
title: set_AfterAnimationType()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نوع انیمیشن پس از اثر تعریف می‌کند. مقدار AfterAnimationType را بنویسید.
type: docs
weight: 235
url: /fa/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) متد

یک نوع انیمیشن پس از اثر تعریف می‌کند. بنویسید [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین افکت اسلاید اول.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// تغییر افکت After animation به "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## موارد مرتبط

* Enum [AfterAnimationType](../../afteranimationtype/)
* کلاس [IEffect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)