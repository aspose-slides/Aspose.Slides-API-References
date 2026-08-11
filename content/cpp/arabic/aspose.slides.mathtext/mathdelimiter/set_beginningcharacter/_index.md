---
title: set_BeginningCharacter()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "Delimiter Beginning Character يحدد حرف الفاصل الابتدائي أو الحرف الافتتاحي. الفواصل الرياضية هي أحرف تغليف مثل الأقواس المستديرة، والأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('."
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) طريقة

Delimiter Beginning Character يحدد الحرف الفاصل الابتدائي، أو الحرف الافتتاحي. الفواصل الرياضية هي أحرف تغليف مثل الأقواس المستديرة، والأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## انظر أيضاً

* الصنف [MathDelimiter](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)