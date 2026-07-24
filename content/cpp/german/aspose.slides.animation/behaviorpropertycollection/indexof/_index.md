---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt den Index eines bestimmten Elements in der IList.
type: docs
weight: 40
url: /de/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const Methode


Bestimmt den Index eines bestimmten Elements in [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Das Objekt, das im [IList](../../../system.collections.generic/ilist/) zu finden ist. |

### Rückgabewert

Der Index von *item*, wenn er in der Liste gefunden wird; andernfalls -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const Methode


Bestimmt den Index eines bestimmten Elements anhand des Eigenschaftswerts in [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | Wert der Eigenschaft |

### Rückgabewert

Der Index der Eigenschaft mit dem angegebenen Wert

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBehaviorProperty](../../ibehaviorproperty/)
* Klasse [BehaviorPropertyCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)