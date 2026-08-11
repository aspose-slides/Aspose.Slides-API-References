---
title: Enclose()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضمن العناصر الفرعية لهذا المكوّن داخل أحرف محددة مثل الأقواس أو أحرف أخرى كإطار
type: docs
weight: 222
url: /ar/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) طريقة

يضمن العناصر الفرعية لهذا المكوّن داخل أحرف محددة مثل الأقواس أو أحرف أخرى كإطار

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char16_t | الحرف البادئ (عادة القوس الأيسر) |
| endingCharacter | char16_t | الحرف النهائي (عادة القوس الأيمن) |

### قيمة الإرجاع

عنصر الرياضيات من النوع [IMathDelimiter](../../imathdelimiter/) الذي يتضمن الأحرف المحددة كإطار

## ملاحظات

مثال:
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) طريقة

يضمن العناصر الفرعية لهذا المكوّن داخل أحرف محددة مثل الأقواس أو غيرها كإطار ويحدّدها بحرف فاصل

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char16_t | الحرف البادئ (عادة القوس الأيسر) |
| endingCharacter | char16_t | الحرف النهائي (عادة القوس الأيمن) |
| separatorCharacter | char16_t | حرف الفاصل |

### قيمة الإرجاع

عنصر الرياضيات من النوع [IMathDelimiter](../../imathdelimiter/) الذي يتضمن الأحرف المحددة كإطار وفاصل

## ملاحظات

مثال:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathDelimiter](../../imathdelimiter/)
* فئة [MathBlock](../)
* نطاق الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)