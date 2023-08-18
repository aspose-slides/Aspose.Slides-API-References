---
title: Divide()
second_title: Aspose.Slides for C++ API Reference
description: Creates a fraction with this numerator and specified denominator
type: docs
weight: 27
url: /aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) method


Creates a fraction with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominator |

### Return Value

new fraction
## Remarks



Example: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) method


Creates a fraction with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominator |

### Return Value

new fraction
## Remarks



Example: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) method


Creates a fraction of the specified type with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominator |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type: Bar, NoBar, Skewed, Linear |

### Return Value

new fraction
## Remarks



Example: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) method


Creates a fraction of the specified type with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominator |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type: Bar, NoBar, Skewed, Linear |

### Return Value

new fraction
## Remarks



Example: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", Aspose::Slides::MathText::MathFractionTypes::Linear);
```

## See Also

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)