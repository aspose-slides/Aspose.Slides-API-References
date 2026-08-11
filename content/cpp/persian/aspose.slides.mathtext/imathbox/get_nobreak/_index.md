---
title: get_NoBreak()
second_title: مرجع API Aspose.Slides برای C++
description: "بدون شکست. این ویژگی خاصیت \"unbreakable\" را بر روی جعبه شیء مشخص می‌کند. وقتی مقدار true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که از بیش از یک عملگر باینری تشکیل شده‌اند مهم باشد. وقتی این عنصر مشخص نشود، شکست‌ها می‌توانند در داخل جعبه رخ دهند. پیش‌فرض: true"
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() متد


بدون شکست. این ویژگی خصوصیت "unbreakable" را در جعبه شیء مشخص می‌کند. زمانی که مقدار true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند مهم باشد. زمانی که این عنصر مشخص نشده باشد، شکست‌ها می‌توانند درون جعبه رخ دهند. پیش‌فرض: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## توضیحات


مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## موارد مرتبط

* کلاس [IMathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)