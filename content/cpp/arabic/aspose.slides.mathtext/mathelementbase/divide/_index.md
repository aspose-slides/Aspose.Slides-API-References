---
title: Divide()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كسرًا باستخدام هذا البسط والمقام المحدد
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) method

ينشئ كسرًا باستخدام هذا البسط والمقام المحدد

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | المقام |

### قيمة الإرجاع

كسر جديد
## ملاحظات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) method

ينشئ كسرًا باستخدام هذا البسط والمقام المحدد

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | المقام |

### قيمة الإرجاع

كسر جديد
## ملاحظات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) method

ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | المقام |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع الكسر: Bar, NoBar, Skewed, Linear |

### قيمة الإرجاع

كسر جديد
## ملاحظات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) method

ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | المقام |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع الكسر: Bar, NoBar, Skewed, Linear |

### قيمة الإرجاع

كسر جديد
## ملاحظات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## انظر أيضا

* تعداد [MathFractionTypes](../../mathfractiontypes/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathFraction](../../imathfraction/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)