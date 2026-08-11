---
title: set_NoBreak()
second_title: Aspose.Slides برای C++ مرجع API
description: "بدون شکست. این ویژگی خصوصیت \"unbreakable\" را بر روی جعبه شیء مشخص می‌کند. وقتی true باشد، هیچ شکست خطی در داخل جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند مهم باشد. وقتی این عنصر مشخص نشده باشد، شکست‌ها می‌توانند در داخل جعبه رخ دهند. پیش‌فرض: true"
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) متد

بدون شکست. این ویژگی خصوصیت \"unbreakable\" را روی جعبه شیء مشخص می‌کند. زمانی که true باشد، هیچ شکست خطی در داخل جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که از بیش از یک عملگر باینری تشکیل شده‌اند مهم باشد. زمانی که این عنصر مشخص نشده باشد، شکست‌ها می‌توانند در داخل جعبه رخ دهند. پیش‌فرض: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## توضیحات

مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## موارد مرتبط

* کلاس [IMathBox](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)