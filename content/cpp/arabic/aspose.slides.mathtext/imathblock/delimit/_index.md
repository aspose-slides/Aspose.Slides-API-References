---
title: Delimit()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يحدّ جميع العناصر الفرعية بحرف الفاصل (بدون الأقواس)
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) طريقة

يحدد حدود جميع العناصر الفرعية باستخدام حرف الفاصل (بدون الأقواس)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char16_t | حرف يُستخدم كفاصل |

### قيمة الإرجاع

مثيل من عنصر [IMathDelimiter](../../imathdelimiter/)

## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathDelimiter](../../imathdelimiter/)
* فئة [IMathBlock](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)