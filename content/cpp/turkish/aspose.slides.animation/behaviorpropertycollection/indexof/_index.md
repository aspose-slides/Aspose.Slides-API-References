---
title: IndexOf()
second_title: Aspose.Slides C++ API Referansı
description: IList içinde belirli bir öğenin indeksini belirler.
type: docs
weight: 40
url: /tr/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const metod

Belirli bir öğenin [IList](../../../system.collections.generic/ilist/) içindeki indeksini belirler.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [IList](../../../system.collections.generic/ilist/) içinde bulunacak nesne. |

### Dönüş Değeri

Liste içinde bulunduysa *item* öğesinin indeksi; aksi takdirde -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const metod

[IList](../../../system.collections.generic/ilist/) içinde özellik değerine göre belirli bir öğenin indeksini belirler.

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | özelliğin değeri |

### Dönüş Değeri

Belirtilen değere sahip özelliğin indeksi

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IBehaviorProperty](../../ibehaviorproperty/)
* Sınıf [BehaviorPropertyCollection](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)