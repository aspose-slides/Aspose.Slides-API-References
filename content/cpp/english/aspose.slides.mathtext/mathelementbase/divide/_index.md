---
title: Divide()
second_title: Aspose.Slides for C++ API Reference
description: Creates a fraction with this numerator and specified denominator
type: docs
weight: 14
url: /aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) method


Creates a fraction with this numerator and specified denominator

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |

### Return Value

new fraction
## Remarks



Example: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) method


Creates a fraction with this numerator and specified denominator

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
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
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) method


Creates a fraction of the specified type with this numerator and specified denominator

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |
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

## MathElementBase::Divide(System::String, MathFractionTypes) method


Creates a fraction of the specified type with this numerator and specified denominator

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
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
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## See Also

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)