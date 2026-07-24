---
title: Reorder()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır.
type: docs
weight: 300
url: /tr/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metot

Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Şeklin yerleştirileceği sıfır bazlı hedef indeks. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Koleksiyon içinde taşınacak [IShape](../../ishape/). |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metot

Belirtilen şekilleri şekil koleksiyonunda hareket ettirir ve verilen indeks'ten itibaren yerleştirir.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | İlk belirtilen şeklin yerleştirileceği sıfır bazlı hedef indeks; sonraki şekiller sağlanan sırayla yerleştirilir. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Koleksiyon içinde taşınacak bir veya daha fazla [IShape](../../ishape/) örneği. |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IShape](../../ishape/)
* Sınıf [IShapeCollection](../)
* İsim Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)