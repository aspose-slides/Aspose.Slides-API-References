---
title: CreateMathFraction()
second_title: Aspose.Slides برای مرجع API C++
description: یک کسر ریاضی ایجاد می‌کند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) متد

یک کسر ریاضی ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | صورت |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | مخرج |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | نوع کسر |

### مقدار بازگشت

کسر ریاضی جدید [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

یک کسر ریاضی ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | صورت |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | مخرج |

### مقدار بازگشت

کسر ریاضی جدید [IMathFraction](../../imathfraction/)

## موارد مرتبط

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathFraction](../../imathfraction/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathFractionFactory](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)