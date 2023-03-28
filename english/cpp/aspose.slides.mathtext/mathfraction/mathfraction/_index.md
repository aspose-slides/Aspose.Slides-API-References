---
title: MathFraction()
second_title: Aspose.Slides for C++ API Reference
description: Initializes MathFraction with the specified numerator, denominator and type
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [MathFractionTypes](../../mathfractiontypes/)) constructor


Initializes [MathFraction](../) with the specified numerator, denominator and type

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerator |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type |
## Remarks



Example: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), Aspose::Slides::MathText::MathFractionTypes::Linear);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathFraction::MathFraction([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) constructor


Initializes a [MathFraction](../) of type 'Bar' with the specified numerator and denominator

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerator |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |
## Remarks



Example: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
