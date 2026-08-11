---
title: set_SeparatorCharacter()
second_title: مرجع API ل Aspose.Slides للغة C++
description: "يحدد Delimiter Separator Character الحرف الذي يفصل الوسائط في كائن الفاصل. القيمة الافتراضية: '|'."
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) طريقة

يحدد Delimiter Separator Character الحرف الذي يفصل الوسائط في كائن الفاصل. القيمة الافتراضية: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## انظر أيضًا

* الفئة [MathDelimiter](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)