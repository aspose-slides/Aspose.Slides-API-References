---
title: Contains()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje, zda ICollection obsahuje konkrétní hodnotu.
type: docs
weight: 118
url: /cs/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const metoda

Určuje, zda [ICollection](../../../system.collections.generic/icollection/) obsahuje konkrétní hodnotu.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Vlastnost, kterou je třeba najít v [ICollection](../../../system.collections.generic/icollection/). |

### Návratová hodnota

true, pokud je *item* nalezen v [ICollection](../../../system.collections.generic/icollection/); jinak false.

## BehaviorPropertyCollection::Contains(const System::String\&) const metoda

Určuje, zda [ICollection](../../../system.collections.generic/icollection/) obsahuje konkrétní hodnotu.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | Hodnota vlastnosti, kterou je třeba najít v [ICollection](../../../system.collections.generic/icollection/). |

### Návratová hodnota

true, pokud je *propertyValue* nalezen v [ICollection](../../../system.collections.generic/icollection/); jinak false.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBehaviorProperty](../../ibehaviorproperty/)
* Třída [BehaviorPropertyCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)