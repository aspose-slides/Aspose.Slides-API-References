---
title: get_BaseJustification()
second_title: مرجع API Aspose.Slides برای C++
description: "چیدمان عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center"
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() متد

چیدمان عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. Default: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## موارد مرتبط

* enum [MathVerticalAlignment](../../mathverticalalignment/)
* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)