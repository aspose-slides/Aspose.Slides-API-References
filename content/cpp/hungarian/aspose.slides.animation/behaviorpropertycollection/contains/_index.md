---
title: Contains()
second_title: Aspose.Slides C++ API referenciája
description: Megállapítja, hogy az ICollection tartalmaz-e egy adott értéket.
type: docs
weight: 118
url: /hu/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const metódus

Megállapítja, hogy a [ICollection](../../../system.collections.generic/icollection/) tartalmaz-e egy adott értéket.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | A tulajdonság, amelyet a [ICollection](../../../system.collections.generic/icollection/)-ban keresni kell. |

### Visszatérési érték

igaz, ha az *item* megtalálható a [ICollection](../../../system.collections.generic/icollection/)-ban; egyébként hamis.

## BehaviorPropertyCollection::Contains(const System::String\&) const metódus

Megállapítja, hogy a [ICollection](../../../system.collections.generic/icollection/) tartalmaz-e egy adott értéket.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | A tulajdonság értéke, amelyet a [ICollection](../../../system.collections.generic/icollection/)-ban kell megtalálni. |

### Visszatérési érték

igaz, ha a *propertyValue* megtalálható a [ICollection](../../../system.collections.generic/icollection/)-ban; egyébként hamis.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IBehaviorProperty](../../ibehaviorproperty/)
* Osztály [BehaviorPropertyCollection](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)