---
title: Delimit()
second_title: مرجع API Aspose.Slides للغة C++
description: يفصل العناصر الفرعية باستخدام حرف الفاصل (بدون الأقواس)
type: docs
weight: 209
url: /ar/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) طريقة

يفصل العناصر الفرعية باستخدام حرف الفاصل (بدون الأقواس)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char16_t | حرف الفاصل |

### قيمة الإرجاع

عنصر الرياضيات من النوع [IMathDelimiter](../../imathdelimiter/)

## ملاحظات


مثال: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathDelimiter](../../imathdelimiter/)
* فئة [MathBlock](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)