---
title: Reorder()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Przenosi określony kształt na nową pozycję w kolekcji kształtów.
type: docs
weight: 300
url: /pl/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metoda

Przenosi określony kształt na nową pozycję w kolekcji kształtów.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks docelowy liczony od zera, w którym zostanie umieszczony kształt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Obiekt [IShape](../../ishape/) do przeniesienia w kolekcji. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metoda

Przenosi określone kształty w kolekcji kształtów, umieszczając je począwszy od podanego indeksu.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks docelowy liczony od zera, w którym zostanie umieszczony pierwszy określony kształt; kolejne kształty będą umieszczane w podanej kolejności. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Jedna lub więcej instancji [IShape](../../ishape/) do przeniesienia w kolekcji. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)