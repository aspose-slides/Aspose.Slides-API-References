---
title: Reorder()
second_title: Aspose.Slides для C++ справочник API
description: Перемещает указанную фигуру в новое положение внутри коллекции фигур.
type: docs
weight: 339
url: /ru/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) метод

Перемещает указанную фигуру в новое положение внутри коллекции фигур.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой (начиная с нуля) целевой индекс, куда будет помещена фигура. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для перемещения внутри коллекции. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) метод

Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с заданного индекса.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой (начиная с нуля) целевой индекс, где будет размещена первая указанная фигура; последующие фигуры следуют в указанном порядке. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Один или несколько экземпляров [IShape](../../ishape/) для перемещения внутри коллекции. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)