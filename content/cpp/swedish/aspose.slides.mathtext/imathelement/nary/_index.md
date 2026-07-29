---
title: Nary()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en N-ary-operator
type: docs
weight: 170
url: /sv/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metod

Skapar en N-ary-operator

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | N-ary-operatorns typ |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nedre gräns |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Övre gräns |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) metod

Skapar en N-ary-operator

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | N-ary-operatorns typ |
| lowerLimit | [System::String](../../../system/string/) | Nedre gräns |
| upperLimit | [System::String](../../../system/string/) | Övre gräns |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Se även

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathNaryOperator](../../imathnaryoperator/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)