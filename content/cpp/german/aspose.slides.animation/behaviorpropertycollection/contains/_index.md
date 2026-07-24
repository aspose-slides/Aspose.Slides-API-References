---
title: Contains()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob die ICollection einen bestimmten Wert enthält.
type: docs
weight: 118
url: /de/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const method

Bestimmt, ob [ICollection](../../../system.collections.generic/icollection/) einen bestimmten Wert enthält.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Die Eigenschaft, die im [ICollection](../../../system.collections.generic/icollection/) gesucht werden soll. |

### Rückgabewert

true, wenn *item* im [ICollection](../../../system.collections.generic/icollection/) gefunden wird; andernfalls false.

## BehaviorPropertyCollection::Contains(const System::String\&) const method

Bestimmt, ob [ICollection](../../../system.collections.generic/icollection/) einen bestimmten Wert enthält.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | Wert der Eigenschaft, die im [ICollection](../../../system.collections.generic/icollection/) gesucht werden soll. |

### Rückgabewert

true, wenn *propertyValue* im [ICollection](../../../system.collections.generic/icollection/) gefunden wird; andernfalls false.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBehaviorProperty](../../ibehaviorproperty/)
* Klasse [BehaviorPropertyCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)