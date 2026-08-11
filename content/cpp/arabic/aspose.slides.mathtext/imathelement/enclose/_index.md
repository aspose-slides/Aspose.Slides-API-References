---
title: Enclose()
second_title: مرجع API Aspose.Slides للغة C++
description: يغلق عنصرًا رياضيًا داخل أقواس
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() طريقة

يغلق عنصرًا رياضيًا بين قوسين

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### قيمة الإرجاع

العنصر الرياضي من النوع [IMathDelimiter](../../imathdelimiter/) والذي يتضمن القوسين

## ملاحظات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) طريقة

يغلق هذا العنصر بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char16_t | حرف البداية (عادةً القوس الأيسر) |
| endingCharacter | char16_t | حرف النهاية (عادةً القوس الأيمن) |

### قيمة الإرجاع

العنصر الرياضي من النوع [IMathDelimiter](../../imathdelimiter/) والذي يتضمن الأحرف المحددة كإطار

## ملاحظات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathDelimiter](../../imathdelimiter/)
* فئة [IMathElement](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)