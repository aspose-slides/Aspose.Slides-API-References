---
title: SetUpperLimit()
second_title: Référence API Aspose.Slides pour C++
description: Prend la limite supérieure
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) méthode

Prend la limite supérieure

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)
## Remarques



Exemple:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) méthode

Prend la limite supérieure

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Valeur de retour

Nouvelle instance du type [IMathLimit](../../imathlimit/)
## Remarques



Exemple:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)