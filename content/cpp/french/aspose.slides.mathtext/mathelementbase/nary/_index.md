---
title: Nary()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Crée un opérateur N-aire
type: docs
weight: 157
url: /fr/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode

Crée un opérateur N-aire

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Le type d'opérateur N-aire |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | La limite inférieure |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | La limite supérieure |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) méthode

Crée un opérateur N-aire

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
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
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## Voir aussi

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)