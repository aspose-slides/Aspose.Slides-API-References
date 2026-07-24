---
title: Reorder()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır.
type: docs
weight: 339
url: /tr/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metot

Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Şeklin yerleştirileceği sıfır bazlı hedef indeks. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) koleksiyon içinde taşınacak. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metot

Belirtilen şekilleri şekil koleksiyonunda hareket ettirir ve verilen indeks'ten başlayarak yerleştirir.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | İlk belirtilen şeklin yerleştirileceği sıfır bazlı hedef indeks; sonraki şekiller verilen sıraya göre yerleştirilir. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Koleksiyon içinde taşınacak bir veya daha fazla [IShape](../../ishape/) örneği. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)