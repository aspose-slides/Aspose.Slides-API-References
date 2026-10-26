---
title: set_StopPreviousSound()
second_title: Aspose.Slides برای C++ مرجع API
description: این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند. مقدار bool را بنویسید.
type: docs
weight: 209
url: /fa/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) متد

این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. مقدار **bool** را بنویسید.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین افکت اسلاید اول.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// دریافت اولین افکت اسلاید دوم.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // تغییر افکت دوم Enhancements/Sound به "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## مراجع

* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)