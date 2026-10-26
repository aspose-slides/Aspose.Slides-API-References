---
title: set_DelimiterShape()
second_title: مرجع API Aspose.Slides برای C++
description: "شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. زمانی که MathDelimiterShape::Centered باشد، جداکننده‌ها در اطراف محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان به گونه‌ای تنظیم می‌شوند که تمام ارتفاع محتوای آن‌ها را پوشش دهند. زمانی که MathDelimiterShape::Match باشد، ارتفاع و شکل آن‌ها طوری تغییر می‌کند که دقیقاً با محتوایشان مطابقت داشته باشد."
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) متد


شکل جداکننده‌ها را در شیء جداکننده مشخص می‌کند. زمانی که [MathDelimiterShape::Centered](../../mathdelimitershape/) باشد، جداکننده‌ها در اطراف محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان به گونه‌ای تنظیم می‌شوند که تمام ارتفاع محتوای آن‌ها را پوشش دهند. زمانی که [MathDelimiterShape::Match](../../mathdelimitershape/) باشد، ارتفاع و شکل آن‌ها طوری تغییر می‌کند که دقیقاً با محتوایشان مطابقت داشته باشد.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
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