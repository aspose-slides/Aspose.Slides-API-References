---
title: get_StopPreviousSound()
second_title: Aspose.Slides برای C++ مرجع API
description: این ویژگی مشخص می‌کند آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. خواندنی bool.
type: docs
weight: 196
url: /fa/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() متد

این ویژگی مشخص می‌کند آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. خواندنی **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
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

## موارد مرتبط

* کلاس [IEffect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)