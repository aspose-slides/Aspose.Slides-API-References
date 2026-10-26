---
title: set_EndingCharacter()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: "تحدد خاصية Delimiter Ending Character حرف الفاصل النهائي أو الحرف الختامي. الفواصل الرياضية هي أحرف محيطة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'."
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) طريقة

تحدد خاصية Delimiter Ending Character حرف الفاصل النهائي أو الحرف الختامي. الفواصل الرياضية هي أحرف محيطة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
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