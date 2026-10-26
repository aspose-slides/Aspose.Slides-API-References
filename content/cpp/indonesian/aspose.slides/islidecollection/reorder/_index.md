---
title: Reorder()
second_title: Referensi API Aspose.Slides untuk C++
description: Memindahkan slide dari koleksi ke posisi yang ditentukan.
type: docs
weight: 105
url: /id/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) metode

Memindahkan slide dari koleksi ke posisi yang ditentukan.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks target. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) untuk dipindahkan. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) metode

Memindahkan slide dari koleksi ke posisi yang ditentukan. [Slides](../../) akan ditempatkan mulai dari indeks sesuai urutan mereka muncul dalam daftar.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks target. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) untuk dipindahkan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ISlide](../../islide/)
* Kelas [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)