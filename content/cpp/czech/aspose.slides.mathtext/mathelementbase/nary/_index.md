---
title: Nary()
second_title: Aspose.Slides pro C++ API
description: Vytvoří N-ární operátor
type: docs
weight: 157
url: /cs/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Vytvoří N-ární operátor

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Typ N-árního operátoru |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní mez |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Horní mez |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) method


Vytvoří N-ární operátor

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
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
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## Viz také

* Výčet [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathNaryOperator](../../imathnaryoperator/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)