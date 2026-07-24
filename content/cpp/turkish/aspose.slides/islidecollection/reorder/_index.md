---
title: Reorder()
second_title: Aspose.Slides for C++ API Referansı
description: Slaytı koleksiyondan belirtilen konuma taşır.
type: docs
weight: 105
url: /tr/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) method


Slaytı koleksiyondan belirtilen konuma taşır.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Hedef indeks. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) taşınacak. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) method


Slaytları koleksiyondan belirtilen konuma taşır. [Slides](../../) indeks'ten başlayarak listede göründükleri sırayla yerleştirilecektir.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Hedef indeks. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) taşınacak. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)