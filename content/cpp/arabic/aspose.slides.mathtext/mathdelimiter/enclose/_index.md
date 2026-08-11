---
title: Enclose()
second_title: مرجع API Aspose.Slides للـ C++
description: يحيط عنصر رياضي بأحرف محددة مثل القوس أو أحرف أخرى كإطار
type: docs
weight: 170
url: /ar/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) طريقة

يحيط عنصر رياضي بأحرف محددة مثل القوس أو أحرف أخرى كإطار

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char16_t | حرف البداية (عادة القوس الأيسر) |
| endingCharacter | char16_t | حرف النهاية (عادة القوس الأيمن) |

### قيمة الإرجاع

إذا كان *beginningCharacter* و *endingCharacter* null، يتم تعيين القيم للخصائص المقابلة فقط ولا يتم إنشاء كائن جديد (يعيد هذه الحالة). وإلا، يعيد عنصر رياضي جديد من النوع Delimiter يتضمن الأحرف المحددة كإطار وهذه الحالة من [MathDelimiter](../) مؤطَّرة بداخله.

## ملاحظات



مثال: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathDelimiter](../../imathdelimiter/)
* فئة [MathDelimiter](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)