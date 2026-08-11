---
title: get_DelimiterShape()
second_title: Aspose.Slides برای C++ مرجع API
description: "شکل محدودکننده‌ها را در شیء محدودکننده مشخص می‌کند. زمانی که مقدار MathDelimiterShape::Centered باشد، محدودکننده‌ها حول محور ریاضی متن ریاضی مرکزی می‌شوند و به‌طوری تنظیم می‌شوند که تمام ارتفاع محتویاتشان را پوشش دهند. زمانی که مقدار MathDelimiterShape::Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتویاتشان مطابقت می‌یابد."
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() متد


شکل محدودکننده‌ها را در شیء محدودکننده مشخص می‌کند. زمانی که [MathDelimiterShape::Centered](../../mathdelimitershape/) باشد، محدودکننده‌ها حول محور ریاضی متن ریاضی مرکزی می‌شوند و به گونه‌ای تنظیم می‌شوند که تمام ارتفاع محتویاتشان را پوشش دهند. زمانی که [MathDelimiterShape::Match](../../mathdelimitershape/) باشد، ارتفاع و شکل آن‌ها به‌طور دقیق برای مطابقت با محتویاتشان تغییر می‌کند.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## توضیحات


مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## موارد مرتبط

* شمارنده [MathDelimiterShape](../../mathdelimitershape/)
* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)