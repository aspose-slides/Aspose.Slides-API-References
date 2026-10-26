---
title: Nary()
second_title: Référence API Aspose.Slides pour C++
description: Crée un opérateur N-aire
type: docs
weight: 170
url: /fr/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode

Crée un opérateur N-aire

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Le type d'opérateur N-aire |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | La limite inférieure |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | La limite supérieure |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) méthode

Crée un opérateur N-aire

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Le type d'opérateur N-aire |
| lowerLimit | [System::String](../../../system/string/) | La limite inférieure |
| upperLimit | [System::String](../../../system/string/) | La limite supérieure |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Voir aussi

* Énumération [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathNaryOperator](../../imathnaryoperator/)
* classe [IMathElement](../)
* classe [String](../../../system/string/)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)