---
title: get_SeparatorCharacter()
second_title: Aspose.Slides لـ C++ مرجع API
description: "تحدد خاصية Delimiter Separator Character الحرف الذي يفصل الوسائط في كائن الفاصل. القيمة الافتراضية: '|'."
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() طريقة

تحدد خاصية Delimiter Separator Character الحرف الذي يفصل الوسائط في كائن الفاصل. القيمة الافتراضية: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## انظر أيضًا

* فئة [MathDelimiter](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)