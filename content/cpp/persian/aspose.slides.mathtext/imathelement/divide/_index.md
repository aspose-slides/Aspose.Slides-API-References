---
title: Divide()
second_title: Aspose.Slides برای C++ مرجع API
description: یک کسر با این صورت و مخرج مشخص ایجاد می‌کند
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) متد


یک کسر با صورت این و مخرج مشخص ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | مخرج |

### مقدار بازگشت

کسر جدید
## توضیحات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) متد


یک کسر با صورت این و مخرج مشخص ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | مخرج |

### مقدار بازگشت

کسر جدید
## توضیحات



مثال: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) متد


یک کسر از نوع مشخص شده با صورت این و مخرج مشخص ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | مخرج |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع کسر: Bar, NoBar, Skewed, Linear |

### مقدار بازگشت

کسر جدید
## توضیحات



مثال: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) متد


یک کسر از نوع مشخص شده با صورت این و مخرج مشخص ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | مخرج |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع کسر: Bar, NoBar, Skewed, Linear |

### مقدار بازگشت

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
* کلاس [IMathFraction](../../imathfraction/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)