---
title: set_BeginningCharacter()
second_title: مرجع Aspose.Slides للغة C++
description: "حرف بداية الفاصل يحدد حرف الفاصل الأولي أو الافتتاحي. الفواصل الرياضية هي أحرف محاطة مثل الأقواس المستديرة والأقواس المربعة والأقواس المعقوفة. القيمة الافتراضية: '('."
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) طريقة

حرف بداية الفاصل يحدد حرف الفاصل الأولي أو الافتتاحي. الفواصل الرياضية هي أحرف محاطة مثل الأقواس المستديرة والأقواس المربعة والأقواس المعقوفة. القيمة الافتراضية: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## انظر أيضًا

* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)