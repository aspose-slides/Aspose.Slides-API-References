---
title: Reorder()
second_title: Referencia de la API de Aspose.Slides para C++
description: Mueve la forma especificada a una nueva posición dentro de la colección de formas.
type: docs
weight: 339
url: /es/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) método

Mueve la forma especificada a una nueva posición dentro de la colección de formas.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice de destino basado en cero donde se colocará la forma. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a mover dentro de la colección. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) método

Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice indicado.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice de destino basado en cero donde se colocará la primera forma especificada; las formas subsiguientes siguen en el orden proporcionado. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Una o más instancias de [IShape](../../ishape/) a mover dentro de la colección. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)