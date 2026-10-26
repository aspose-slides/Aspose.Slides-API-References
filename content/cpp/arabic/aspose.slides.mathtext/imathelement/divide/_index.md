---
title: Divide()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ كسرًا باستخدام هذا البسط والمقام المحدد
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) طريقة

ينشئ كسرًا باستخدام هذا البسط والمقام المحدد

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | المقام |

### قيمة الإرجاع

كسر جديد
## ملاحظات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) طريقة

ينشئ كسرًا باستخدام هذا البسط والمقام المحدد

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | المقام |

### قيمة الإرجاع

كسر جديد
## ملاحظات



مثال: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) طريقة

ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | المقام |
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

## IMathElement::Divide(System::String, MathFractionTypes) طريقة

ينشئ كسرًا من النوع المحدد باستخدام هذا البسط والمقام المحدد

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### الوسائط

| المعامل | النوع | الوصف |
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

## انظر أيضًا

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)