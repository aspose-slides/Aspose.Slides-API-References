---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides برای مرجع API C++
description: تاخیر بین بخش‌های متنی انیمیشنی (کلمات یا حروف) را تعریف می‌کند. یک مقدار مثبت درصد زمان اثر را مشخص می‌کند. یک مقدار منفی تاخیر را بر حسب ثانیه مشخص می‌کند. بنویسید float.
type: docs
weight: 313
url: /fa/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) متد

یک تاخیر بین بخش‌های متن انیمیشن‌دار (کلمات یا حروف) را تعریف می‌کند. یک مقدار مثبت درصد زمان اثر را مشخص می‌کند. یک مقدار منفی تاخیر را بر حسب ثانیه مشخص می‌کند. نویسید **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## یادداشت‌ها

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین افکت اسلاید اول.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// تغییر نوع افکت AnimateText به "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// تنظیم تأخیر بین بخش‌های متنی انیمیشنی به 20% از مدت اثر.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## موارد مرتبط

* کلاس [IEffect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)