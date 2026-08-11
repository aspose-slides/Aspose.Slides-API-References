---
title: get_Character()
second_title: مرجع API Aspose.Slides للـ C++
description: "حرف التجميع القيمة الافتراضية: U+23DF (القوس المعقوف السفلي)"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() طريقة


القيمة الافتراضية لحرف التجميع: U+23DF (القوس المعقوف السفلي)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## ملاحظات


مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// القوس السفلي
```

## انظر أيضًا

* الفئة [IMathGroupingCharacter](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)