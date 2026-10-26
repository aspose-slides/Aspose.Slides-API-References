---
title: Contains()
second_title: Aspose.Slides for C++ API Referansı
description: ICollection içinde belirli bir değerin olup olmadığını belirler.
type: docs
weight: 118
url: /tr/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const method


Belirli bir değerin [ICollection](../../../system.collections.generic/icollection/) içinde olup olmadığını belirler.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [ICollection](../../../system.collections.generic/icollection/) içinde bulunacak özellik. |

### Dönüş Değeri

*item* [ICollection](../../../system.collections.generic/icollection/) içinde bulunursa true; aksi takdirde false.

## BehaviorPropertyCollection::Contains(const System::String\&) const method


Belirli bir değerin [ICollection](../../../system.collections.generic/icollection/) içinde olup olmadığını belirler.

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | [ICollection](../../../system.collections.generic/icollection/) içinde bulunacak özelliğin değeri. |

### Dönüş Değeri

*propertyValue* [ICollection](../../../system.collections.generic/icollection/) içinde bulunursa true; aksi takdirde false.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)