---
title: set_SeparatorCharacter()
second_title: Aspose.Slides لـ C++ مرجع API
description: "Delimiter Separator Character يحدد الحرف الذي يفصل الوسائط في كائن الفاصل. الافتراضي: '|'."
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) طريقة

Delimiter Separator Character يحدد الحرف الذي يفصل الوسائط في كائن الفاصل. الافتراضي: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## انظر أيضًا

* الفئة [IMathDelimiter](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)