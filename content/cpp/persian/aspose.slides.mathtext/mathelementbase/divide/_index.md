---
title: Divide()
second_title: مرجع API Aspose.Slides برای C++
description: یک کسر با این صورت و مخرج مشخص ایجاد می‌کند
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) متد

یک کسر با این صورت و مخرج مشخص ایجاد می‌کند

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | مخرج |

### مقدار بازگشتی

کسر جدید

## توضیحات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) متد

یک کسر با این صورت و مخرج مشخص ایجاد می‌کند

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | مخرج |

### مقدار بازگشتی

کسر جدید

## توضیحات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) متد

یک کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | مخرج |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع کسر: Bar, NoBar, Skewed, Linear |

### مقدار بازگشتی

کسر جدید

## توضیحات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) متد

یک کسر از نوع مشخص با این صورت و مخرج مشخص ایجاد می‌کند

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | مخرج |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع کسر: Bar, NoBar, Skewed, Linear |

### مقدار بازگشتی

کسر جدید

## توضیحات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## موارد مرتبط

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)