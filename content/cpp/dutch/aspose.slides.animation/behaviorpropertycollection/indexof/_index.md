---
title: IndexOf()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt de index van een specifiek item in de IList.
type: docs
weight: 40
url: /nl/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method

Bepaalt de index van een specifiek item in de [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Het object om te vinden in de [IList](../../../system.collections.generic/ilist/). |

### Retourwaarde

De index van *item* indien gevonden in de lijst; anders -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method

Bepaalt de index van een specifiek item op basis van de eigenschapswaarde in de [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | waarde van de eigenschap |

### Retourwaarde

De index van de eigenschap met de opgegeven waarde

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBehaviorProperty](../../ibehaviorproperty/)
* Klasse [BehaviorPropertyCollection](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)