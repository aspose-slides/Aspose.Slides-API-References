---
title: Nary()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy operator N-arny
type: docs
weight: 157
url: /pl/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Tworzy operator N-arny

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Typ operatora N-arny |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolny limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Górny limit |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) metoda

Tworzy operator N-arny

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Typ operatora N-arny |
| lowerLimit | [System::String](../../../system/string/) | Dolny limit |
| upperLimit | [System::String](../../../system/string/) | Górny limit |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## Zobacz także

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathNaryOperator](../../imathnaryoperator/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)