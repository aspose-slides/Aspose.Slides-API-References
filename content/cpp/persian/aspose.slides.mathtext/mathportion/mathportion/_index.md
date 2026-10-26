---
title: MathPortion()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس MathPortion را مقداردهی اولیه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() سازنده


یک نمونه جدید از کلاس [MathPortion](../) را مقداردهی اولیه می‌کند.

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## توضیحات


مثال:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## موارد مرتبط

* کلاس [MathPortion](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)