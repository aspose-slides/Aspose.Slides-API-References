---
title: Divide()
second_title: Aspose.Slides for C++ API Reference
description: Creates a fraction with this numerator and specified denominator
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\>) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::Divide([System::String](../../../system/string/)) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [String](../../../system/string/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::Divide([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\>, [MathFractionTypes](../../mathfractiontypes/)) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::Divide([System::String](../../../system/string/), [MathFractionTypes](../../mathfractiontypes/)) method


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [String](../../../system/string/)
* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
