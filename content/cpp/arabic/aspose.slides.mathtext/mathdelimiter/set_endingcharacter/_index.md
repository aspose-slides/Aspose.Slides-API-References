---
title: set_EndingCharacter()
second_title: مرجع API Aspose.Slides للغة C++
description: "يحدد Delimiter Ending Character حرف الفاصل الختامي أو المغلق. الفواصل الرياضية هي أحرف محيطة مثل الأقواس المستديرة، والأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'."
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) طريقة

Delimiter Ending Character تحدد الحرف الختامي أو الحرف المغلق للفاصل. الفواصل الرياضية هي أحرف محيطة مثل الأقواس المستديرة، والأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## انظر أيضًا

* فئة [MathDelimiter](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)