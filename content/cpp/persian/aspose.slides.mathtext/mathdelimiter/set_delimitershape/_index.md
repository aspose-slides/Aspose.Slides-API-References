---
title: set_DelimiterShape()
second_title: مرجع API Aspose.Slides برای C++
description: "شکل محدوده‌ها را در شیء delimiter مشخص می‌کند. وقتی MathDelimiterShape::Centered باشد، محدوده‌ها حول محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان تنظیم می‌شوند تا تمام ارتفاع محتویات خود را پوشش دهند. وقتی MathDelimiterShape::Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتویاتشان منطبق می‌شود."
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) متد


شکل محدوده‌ها را در شیء delimiter مشخص می‌کند. هنگامی که [MathDelimiterShape::Centered](../../mathdelimitershape/) باشد، محدوده‌ها حول محور ریاضی متن ریاضی متمرکز شده و همچنان تنظیم می‌شوند تا تمام ارتفاع محتویات خود را پوشش دهند. هنگامی که [MathDelimiterShape::Match](../../mathdelimitershape/) باشد، ارتفاع و شکل آن‌ها دقیقاً به محتوایشان منطبق می‌شود.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## ملاحظات


مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## همچنین ببینید

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)