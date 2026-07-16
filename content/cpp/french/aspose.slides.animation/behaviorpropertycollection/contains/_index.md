---
title: Contains()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si l'ICollection contient une valeur spécifique.
type: docs
weight: 118
url: /fr/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const method

Détermine si le [ICollection](../../../system.collections.generic/icollection/) contient une valeur spécifique.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | La propriété à localiser dans le [ICollection](../../../system.collections.generic/icollection/). |

### Valeur de retour

true si *item* est trouvé dans le [ICollection](../../../system.collections.generic/icollection/) ; sinon, false.

## BehaviorPropertyCollection::Contains(const System::String\&) const method

Détermine si le [ICollection](../../../system.collections.generic/icollection/) contient une valeur spécifique.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | Valeur de la propriété à localiser dans le [ICollection](../../../system.collections.generic/icollection/). |

### Valeur de retour

true si *propertyValue* est trouvé dans le [ICollection](../../../system.collections.generic/icollection/) ; sinon, false.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)