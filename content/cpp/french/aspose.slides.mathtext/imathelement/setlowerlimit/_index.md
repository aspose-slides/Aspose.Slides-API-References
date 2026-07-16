---
title: SetLowerLimit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Prend la limite inférieure
type: docs
weight: 157
url: /fr/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) méthode

Prend la limite inférieure

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limite |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)

## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) méthode

Prend la limite inférieure

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limite |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)

## Remarques



Exemple : 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathLimit](../../imathlimit/)
* classe [IMathElement](../)
* classe [String](../../../system/string/)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)