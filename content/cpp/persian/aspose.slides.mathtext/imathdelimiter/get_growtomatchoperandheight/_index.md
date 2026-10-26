---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides برای مرجع API C++
description: رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی true باشد، delimiters به صورت عمودی رشد می‌کند تا با ارتفاع عملوند خود مطابقت داشته باشد. مقدار پیش‌فرض true است
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() متد

رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی true باشد، delimiters به صورت عمودی رشد می‌کند تا با ارتفاع عملوند خود مطابقت داشته باشد. مقدار پیش‌فرض true است.

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## موارد مرتبط

* کلاس [IMathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)