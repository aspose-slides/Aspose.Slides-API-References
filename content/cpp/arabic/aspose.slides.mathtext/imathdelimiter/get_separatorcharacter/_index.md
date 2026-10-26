---
title: get_SeparatorCharacter()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "Delimiter Separator Character يحدد الحرف الذي يفصل بين المت변ات في كائن الفاصل. الافتراضي: '|'."
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() طريقة

Delimiter Separator Character يحدد الحرف الذي يفصل بين المتغيرات في كائن الفاصل. الافتراضي: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## انظر أيضًا

* الفئة [IMathDelimiter](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)