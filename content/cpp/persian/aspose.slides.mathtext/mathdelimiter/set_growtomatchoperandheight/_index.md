---
title: set_GrowToMatchOperandHeight()
second_title: مرجع API Aspose.Slides برای C++
description: رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، delimiters به صورت عمودی رشد می‌کند تا با ارتفاع operand خود مطابقت داشته باشد. مقدار پیش‌فرض true است
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) متد

رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی true باشد، delimiters به صورت عمودی رشد می‌کند تا با ارتفاع operand خود مطابقت داشته باشد. مقدار پیش‌فرض true است.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## توضیحات

مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## مراجع

* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)