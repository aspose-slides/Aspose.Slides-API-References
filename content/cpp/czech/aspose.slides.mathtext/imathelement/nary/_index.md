---
title: Nary()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří N-ární operátor
type: docs
weight: 170
url: /cs/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Vytvoří N-ární operátor

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Typ N-árního operátoru |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolní mez |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Horní mez |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) metoda


Vytvoří N-ární operátor

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Typ N-árního operátoru |
| lowerLimit | [System::String](../../../system/string/) | Dolní mez |
| upperLimit | [System::String](../../../system/string/) | Horní mez |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Viz také

* Výčet [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathNaryOperator](../../imathnaryoperator/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)