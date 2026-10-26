---
title: get_NoBreak()
second_title: Aspose.Slides برای مرجع API C++
description: "بدون شکست این ویژگی خصوصیت \"غیرقابل شکست\" را بر روی جعبه شیء تعیین می‌کند. وقتی مقدار true باشد، هیچ شکست خطی می‌تواند در داخل جعبه رخ دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند، مهم باشد. وقتی این عنصر مشخص نشده باشد، ممکن است شکست‌ها داخل جعبه رخ دهند. پیش‌فرض: true"
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() متد

بدون شکست این ویژگی ویژگی \"غیرقابل شکست\" را بر روی جعبه شیء مشخص می‌کند. هنگامی که مقدار true باشد، هیچ توقف خطی نمی‌تواند در داخل جعبه رخ دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند، مهم باشد. وقتی این عنصر مشخص نشده باشد، می‌تواند توقف‌ها در داخل جعبه رخ دهد. پیش‌فرض: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## توضیحات

مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## موارد مرتبط

* کلاس [MathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)