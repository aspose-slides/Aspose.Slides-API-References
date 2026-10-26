---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan indeks dari item tertentu dalam IList.
type: docs
weight: 40
url: /id/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const metode

Menentukan indeks dari item tertentu dalam [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Objek yang akan dicari dalam [IList](../../../system.collections.generic/ilist/). |

### Nilai Kembali

Indeks *item* jika ditemukan dalam daftar; jika tidak, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const metode

Menentukan indeks dari item tertentu berdasarkan nilai properti dalam [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | nilai properti |

### Nilai Kembali

Indeks properti dengan nilai yang ditentukan

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)