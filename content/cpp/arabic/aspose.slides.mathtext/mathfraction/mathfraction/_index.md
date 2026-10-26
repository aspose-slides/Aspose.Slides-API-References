---
title: MathFraction()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتهيئة MathFraction باستخدام البسط والمقام والنوع المحددين
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) مُنشئ


يقوم بتهيئة [MathFraction](../) باستخدام البسط والمقام والنوع المحددين

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerator |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type |
## ملاحظات



مثال: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) مُنشئ


يقوم بتهيئة [MathFraction](../) من النوع 'Bar' باستخدام البسط والمقام المحددين

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerator |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |
## ملاحظات



مثال: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## راجع أيضاً

* تعداد [MathFractionTypes](../../mathfractiontypes/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صف [IMathElement](../../imathelement/)
* صف [MathFraction](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)