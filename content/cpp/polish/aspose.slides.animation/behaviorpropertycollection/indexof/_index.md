---
title: IndexOf()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa indeks konkretnego elementu w IList.
type: docs
weight: 40
url: /pl/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method

Określa indeks określonego elementu w [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Obiekt, który ma zostać odnaleziony w [IList](../../../system.collections.generic/ilist/). |

### Wartość zwracana

Indeks *item* jeśli zostanie znaleziony na liście; w przeciwnym razie -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method

Określa indeks określonego elementu na podstawie wartości właściwości w [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | wartość właściwości |

### Wartość zwracana

Indeks właściwości o określonej wartości

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IBehaviorProperty](../../ibehaviorproperty/)
* Klasa [BehaviorPropertyCollection](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)