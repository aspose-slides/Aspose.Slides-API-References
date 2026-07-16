---
title: IndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine l'index d'un élément spécifique dans l'IList.
type: docs
weight: 40
url: /fr/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const méthode

Détermine l'index d'un élément spécifique dans le [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | L'objet à localiser dans le [IList](../../../system.collections.generic/ilist/). |

## Valeur de retour

L'index de *item* s'il est trouvé dans la liste ; sinon, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const méthode

Détermine l'index d'un élément spécifique par valeur de propriété dans le [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | valeur de la propriété |

## Valeur de retour

L'index de la propriété avec la valeur spécifiée

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBehaviorProperty](../../ibehaviorproperty/)
* Classe [BehaviorPropertyCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)