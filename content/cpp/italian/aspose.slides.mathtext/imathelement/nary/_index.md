---
title: Nary()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un operatore N-ario
type: docs
weight: 170
url: /it/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Crea un operatore N-ario

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Il tipo di operatore N-ario |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Il limite inferiore |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Il limite superiore |

### Valore di ritorno

Nuova istanza del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Osservazioni

Esempio: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) method

Crea un operatore N-ario

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Il tipo di operatore N-ario |
| lowerLimit | [System::String](../../../system/string/) | Il limite inferiore |
| upperLimit | [System::String](../../../system/string/) | Il limite superiore |

### Valore di ritorno

Nuova istanza del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Osservazioni

Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Vedi anche

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathNaryOperator](../../imathnaryoperator/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)