---
title: get_DelimiterShape()
second_title: Aspose.Slides برای C++ مرجع API
description: "شکل delimiters را در شی delimiter مشخص می‌کند. هنگامی که مقدار MathDelimiterShape::Centered باشد، delimiters در اطراف محور ریاضی متن ریاضی مرکزی می‌شوند و همچنان به گونه ای تنظیم می‌شوند که تمام ارتفاع محتوای آنها را پوشش دهند. هنگامی که مقدار MathDelimiterShape::Match باشد، ارتفاع و شکل آنها به طور دقیق برای تطبیق با محتوا تغییر می‌کند."
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() متد

شکل delimiters را در شی delimiter مشخص می‌کند. هنگامی که [MathDelimiterShape::Centered](../../mathdelimitershape/) است، delimiters در اطراف محور ریاضی متن ریاضی مرکزی می‌شوند و همچنان به گونه‌ای تنظیم می‌شوند که تمام ارتفاع محتوای آنها را پوشش دهند. هنگامی که [MathDelimiterShape::Match](../../mathdelimitershape/) است، ارتفاع و شکل آنها به‌طور دقیق برای تطبیق با محتوا تغییر می‌کند.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## موارد مرتبط

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* کلاس [IMathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)