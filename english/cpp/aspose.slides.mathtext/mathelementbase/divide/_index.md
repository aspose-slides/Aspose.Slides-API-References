---
title: Divide()
second_title: Aspose.Slides for C++ API Reference
description: Creates a fraction with this numerator and specified denominator
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::Divide([System::String](../../../system/string/)) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [String](../../../system/string/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::Divide([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [MathFractionTypes](../../mathfractiontypes/)) method


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
auto fraction = numerator->Divide(denumerator, Aspose::Slides::MathText::MathFractionTypes::Linear);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::Divide([System::String](../../../system/string/), [MathFractionTypes](../../mathfractiontypes/)) method


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
auto fraction = numerator->Divide(u"y", Aspose::Slides::MathText::MathFractionTypes::Linear);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [String](../../../system/string/)
* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
