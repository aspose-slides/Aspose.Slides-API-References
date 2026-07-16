---
title: SetUpperLimit()
second_title: Référence API Aspose.Slides pour C++
description: Prend la limite supérieure
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) méthode

Prend la limite supérieure

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) méthode

Prend la limite supérieure

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)