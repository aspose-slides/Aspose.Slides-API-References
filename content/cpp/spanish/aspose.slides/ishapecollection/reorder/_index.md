---
title: Reorder()
second_title: Referencia de la API de Aspose.Slides para C++
description: Mueve la forma especificada a una nueva posición dentro de la colección de formas.
type: docs
weight: 300
url: /es/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) método

Mueve la forma especificada a una nueva posición dentro de la colección de formas.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice de destino basado en cero donde se colocará la forma. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | El [IShape](../../ishape/) a mover dentro de la colección. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) método

Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice dado.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice de destino basado en cero donde se colocará la primera forma especificada; las formas subsecuentes siguen en el orden proporcionado. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Una o más instancias de [IShape](../../ishape/) a mover dentro de la colección. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IShape](../../ishape/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)