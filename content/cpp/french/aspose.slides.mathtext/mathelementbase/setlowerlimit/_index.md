---
title: SetLowerLimit()
second_title: Référence API Aspose.Slides pour C++
description: Prend la limite inférieure
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) méthode


Prend la limite inférieure

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limite |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)
## Remarques



Exemple :
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) méthode


Prend la limite inférieure

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
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
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)