---
title: get_EndingCharacter()
second_title: مرجع API Aspose.Slides للغة C++
description: "يحدد حرف النهاية للحد الفاصل حرف النهاية أو الإغلاق. الحدود الرياضية هي أحرف إغلاقية مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'."
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() طريقة

Delimiter Ending Character يحدد حرف النهاية أو الإغلاق للحد الفاصل. الحدود الرياضية هي أحرف إغلاقيّة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## انظر أيضًا

* فئة [MathDelimiter](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)