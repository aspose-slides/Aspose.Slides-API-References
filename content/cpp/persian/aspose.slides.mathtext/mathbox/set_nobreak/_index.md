---
title: set_NoBreak()
second_title: Aspose.Slides برای مستندات API C++
description: "بدون شکست این ویژگی ویژگی \"unbreakable\" را برای جعبه شیء مشخص می‌کند. وقتی مقدار true باشد، هیچ شکست خطی در داخل جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند مهم باشد. وقتی این عنصر مشخص نشود، شکست‌ها می‌توانند داخل جعبه رخ دهند. پیش‌فرض: true"
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) متد

No break این ویژگی مشخص می‌کند که ویژگی "unbreakable" روی جعبه شیء تنظیم شده است. وقتی مقدار true باشد، هیچ شکست خطی داخل جعبه امکان‌پذیر نیست. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند مهم باشد. وقتی این عنصر مشخص نشود، شکست‌ها می‌توانند داخل جعبه رخ دهند. پیش‌فرض: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## توضیحات

مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## موارد مرتبط

* کلاس [MathBox](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)