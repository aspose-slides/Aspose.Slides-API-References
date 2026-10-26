---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides برای C++ مرجع API
description: رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوند خود منطبق شوند. مقدار پیش‌فرض true است
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() متد

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter. When true, the delimiters grows vertically to match its operand height. مقدار پیش‌فرض true است

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## توضیحات

مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## موارد مرتبط

* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)