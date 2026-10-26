---
title: get_BeginningCharacter()
second_title: Aspose.Slides للغة C++ مرجع API
description: "حرف البداية للحدود يحدد الحرف الفاصل البادئ أو الافتتاحي. الحدود الرياضية هي أحرف محيطة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. الافتراضي: '('."
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() طريقة


حرف البداية للحدود يحدد الحرف الفاصل البادئ أو الافتتاحي. الحدود الرياضية هي أحرف محيطة مثل الأقواس المستديرة، الأقواس المربعة، والأقواس المعقوفة. الافتراضي: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## ملاحظات


مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## انظر أيضًا

* فئة [MathDelimiter](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)