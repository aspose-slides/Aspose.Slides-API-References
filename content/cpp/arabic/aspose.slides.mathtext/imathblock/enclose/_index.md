---
title: Enclose()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحيط العناصر الفرعية لهذا الكتلة بأحرف محددة مثل الأقواس أو غيرها كإطار ويحددها بحرف فاصل
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) طريقة

يحيط العنصر الفرعي لهذا الكتلة بأحرف محددة مثل الأقواس أو غيرها كإطار ويحددها بحرف فاصل

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### المعاملات

| المعامل | نوع | وصف |
| --- | --- | --- |
| beginningCharacter | char16_t | حرف البداية (عادة القوس الأيسر) |
| endingCharacter | char16_t | حرف النهاية (عادة القوس الأيمن) |
| separatorCharacter | char16_t | حرف الفاصل |

### قيمة الإرجاع

عنصر رياضي من النوع [IMathDelimiter](../../imathdelimiter/) الذي يضم الأحرف المحددة كإطار وفاصل
## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathDelimiter](../../imathdelimiter/)
* فئة [IMathBlock](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)