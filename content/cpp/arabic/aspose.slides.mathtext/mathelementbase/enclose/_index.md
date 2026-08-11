---
title: Enclose()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُحْيِطُ بعنصر رياضي بين قوسين
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() طريقة

يُحْيِطُ بعنصر رياضي بين قوسين

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### قيمة الإرجاع

العنصر الرياضي من النوع [IMathDelimiter](../../imathdelimiter/) الذي يتضمن القوسين
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) طريقة


يُحْيِطُ بعنصر رياضي بأحرف محددة مثل القوس أو أحرف أخرى كإطار

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### معلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char16_t | الحرف الابتدائي (عادةً القوس الأيسر) |
| endingCharacter | char16_t | الحرف النهائي (عادةً القوس الأيمن) |

### قيمة الإرجاع

العنصر الرياضي من النوع [IMathDelimiter](../../imathdelimiter/) الذي يتضمن الأحرف المحددة كإطار
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)