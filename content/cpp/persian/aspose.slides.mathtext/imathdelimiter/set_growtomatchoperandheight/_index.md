---
title: set_GrowToMatchOperandHeight()
second_title: مرجع API Aspose.Slides برای C++
description: رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده به صورت عمودی رشد می‌کند تا با ارتفاع عملوند خود مطابقت داشته باشد. مقدار پیش‌فرض true است
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) متد

رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده به صورت عمودی رشد می‌کند تا با ارتفاع عملوند خود مطابقت داشته باشد. مقدار پیش‌فرض true است.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## مراجع

* کلاس [IMathDelimiter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)