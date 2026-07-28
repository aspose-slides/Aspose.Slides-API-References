---
title: IndexOf()
second_title: Aspose.Slides C++ API Referenciája
description: Meghatározza egy adott elem indexét az IList-ban.
type: docs
weight: 40
url: /hu/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method


Meghatározza egy adott elem indexét a [IList](../../../system.collections.generic/ilist/)-ben.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | A keresett objektum a [IList](../../../system.collections.generic/ilist/)-ban. |

### Return Value

Az *item* indexe, ha megtalálható a listában; egyébként -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method


Meghatározza egy adott elem indexét a tulajdonságérték alapján a [IList](../../../system.collections.generic/ilist/)-ban.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | a tulajdonság értéke |

### Return Value

A megadott értékkel rendelkező tulajdonság indexe

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IBehaviorProperty](../../ibehaviorproperty/)
* Osztály [BehaviorPropertyCollection](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)