---
title: set_BaseJustification()
second_title: Aspose.Slides برای C++ API Reference
description: "توضیح می‌دهد که تراز عمودی نسبت به متن اطراف چگونه باشد. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center"
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) متد


توضیح می‌دهد که تراز عمودی نسبت به متن اطراف چگونه باشد. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## توضیحات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## موارد مرتبط

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)