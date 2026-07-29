---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer indexet för ett specifikt objekt i IList.
type: docs
weight: 40
url: /sv/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const metod

Bestämmer indexet för ett specifikt item i [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Objektet att hitta i [IList](../../../system.collections.generic/ilist/). |

### Returvärde

Indexet för *item* om det finns i listan; annars -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const metod

Bestämmer indexet för ett specifikt item efter egenskapsvärde i [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | värde av egenskapen |

### Returvärde

Indexet för egenskapen med det angivna värdet

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IBehaviorProperty](../../ibehaviorproperty/)
* Klass [BehaviorPropertyCollection](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)