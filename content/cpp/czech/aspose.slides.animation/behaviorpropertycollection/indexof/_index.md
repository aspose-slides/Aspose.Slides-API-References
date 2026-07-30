---
title: IndexOf()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje index konkrétní položky v IList.
type: docs
weight: 40
url: /cs/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const metoda

Určuje index konkrétní položky v [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Objekt, který se má vyhledat v [IList](../../../system.collections.generic/ilist/). |

### Návratová hodnota

Index *item* pokud je nalezen v seznamu; jinak -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const metoda

Určuje index konkrétní položky podle hodnoty vlastnosti v [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | hodnota vlastnosti |

### Návratová hodnota

Index vlastnosti se zadanou hodnotou

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBehaviorProperty](../../ibehaviorproperty/)
* Třída [BehaviorPropertyCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)