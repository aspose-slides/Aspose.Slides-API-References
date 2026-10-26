---
title: get_EndingCharacter()
second_title: Aspose.Slides لـ C++ مرجع API
description: "تحدد خاصية Delimiter Ending Character حرف النهاية أو الإغلاق للحد الفاصل. الحدود الرياضية هي أحرف إغلاق مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'."
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() طريقة


Delimiter Ending Character يحدد حرف النهاية أو الإغلاق للحد الفاصل. الحدود الرياضية هي أحرف إغلاق مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## ملاحظات


مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## انظر أيضًا

* الفئة [IMathDelimiter](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)