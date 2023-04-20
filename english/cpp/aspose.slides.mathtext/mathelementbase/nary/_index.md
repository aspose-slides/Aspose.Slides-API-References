---
title: Nary()
second_title: Aspose.Slides for C++ API Reference
description: Creates a N-ary operator
type: docs
weight: 157
url: /cpp/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates a N-ary operator

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The upper limit |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(Aspose::Slides::MathText::MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) method


Creates a N-ary operator

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::String](../../../system/string/) | The lower limit |
| upperLimit | [System::String](../../../system/string/) | The upper limit |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(Aspose::Slides::MathText::MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## See Also

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)