---
title: get_StopPreviousSound()
second_title: مرجع API Aspose.Slides برای C++
description: این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند. خوانده می‌شود bool.
type: docs
weight: 196
url: /fa/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() متد

این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. خوانده می‌شود **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین اثر اسلاید اول.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// دریافت اولین اثر اسلاید دوم.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // تغییر اثر دوم Enhancements/Sound به "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## موارد مرتبط

* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)