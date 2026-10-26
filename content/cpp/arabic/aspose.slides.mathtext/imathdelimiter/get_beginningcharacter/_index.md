---
title: get_BeginningCharacter()
second_title: مرجع Aspose.Slides للغة C++
description: "Delimiter Beginning Character يحدد الحرف الفاصل في البداية أو الفاصل الافتتاحي. الفواصل الرياضية هي أحرف محيطة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('."
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() طريقة


Delimiter Beginning Character يحدد حرف الفاصل في البداية أو الفاصل الافتتاحي. الفواصل الرياضية هي أحرف محيطة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## ملاحظات


مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## انظر أيضاً

* فئة [IMathDelimiter](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)