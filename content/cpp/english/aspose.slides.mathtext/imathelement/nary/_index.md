---
title: Nary()
second_title: Aspose.Slides for C++ API Reference
description: Creates a N-ary operator
type: docs
weight: 170
url: /aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates a N-ary operator

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | The lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | The upper limit |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) method


Creates a N-ary operator

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
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
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## See Also

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)