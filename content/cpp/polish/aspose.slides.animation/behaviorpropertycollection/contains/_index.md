---
title: Contains()
second_title: Aspose.Slides dla C++ – referencja API
description: Określa, czy ICollection zawiera określoną wartość.
type: docs
weight: 118
url: /pl/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const metoda

Określa, czy [ICollection](../../../system.collections.generic/icollection/) zawiera określoną wartość.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Właściwość do zlokalizowania w [ICollection](../../../system.collections.generic/icollection/). |

### Wartość zwracana

true, jeśli *item* zostanie znaleziony w [ICollection](../../../system.collections.generic/icollection/); w przeciwnym razie false.

## BehaviorPropertyCollection::Contains(const System::String\&) const metoda

Określa, czy [ICollection](../../../system.collections.generic/icollection/) zawiera określoną wartość.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | Wartość właściwości do zlokalizowania w [ICollection](../../../system.collections.generic/icollection/). |

### Wartość zwracana

true, jeśli *propertyValue* zostanie znaleziony w [ICollection](../../../system.collections.generic/icollection/); w przeciwnym razie false.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IBehaviorProperty](../../ibehaviorproperty/)
* Klasa [BehaviorPropertyCollection](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)