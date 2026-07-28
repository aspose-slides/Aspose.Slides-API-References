---
title: Nary()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy operator N-arny
type: docs
weight: 170
url: /pl/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Tworzy operator N-arny

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | The lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | The upper limit |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) metoda

Tworzy operator N-arny

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::String](../../../system/string/) | The lower limit |
| upperLimit | [System::String](../../../system/string/) | The upper limit |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Zobacz także

* Wyliczenie [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathNaryOperator](../../imathnaryoperator/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)