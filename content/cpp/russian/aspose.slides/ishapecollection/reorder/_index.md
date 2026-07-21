---
title: Reorder()
second_title: Aspose.Slides для C++ справочник API
description: Перемещает указанную фигуру в новое положение внутри коллекции фигур.
type: docs
weight: 300
url: /ru/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) method


Перемещает указанный объект в новое положение внутри коллекции объектов.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Целевой индекс с нулевой отсчётной точкой, где будет размещён объект. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для перемещения внутри коллекции. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) method


Перемещает указанные объекты внутри коллекции, начиная с заданного индекса.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Целевой индекс с нулевой отсчётной точкой, где будет размещена первая указанная фигура; последующие фигуры размещаются в указанном порядке. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Один или несколько [IShape](../../ishape/) экземпляров для перемещения внутри коллекции. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [IShape](../../ishape/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)