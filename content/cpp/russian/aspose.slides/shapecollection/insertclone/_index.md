---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу.
type: docs
weight: 560
url: /ru/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) метод

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой-based индекс, в который будет вставлена склонированная фигура. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для клонирования. |
| x | **float** | Координата x рамки склонированной фигуры, в пунктах. |
| y | **float** | Координата y рамки склонированной фигуры, в пунктах. |
| width | **float** | Ширина рамки склонированной фигуры, в пунктах. |
| height | **float** | Высота рамки склонированной фигуры, в пунктах. |

### Return Value

Ново созданный [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) метод

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу. Новая фигура сохраняет ширину и высоту *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой-based индекс, в который будет вставлена склонированная фигура. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для клонирования. |
| x | **float** | Координата x рамки склонированной фигуры, в пунктах. |
| y | **float** | Координата y рамки склонированной фигуры, в пунктах. |

### Return Value

Ново созданный [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) метод

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу. Склонированная фигура сохраняет оригинальную позицию и размер.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой-based индекс, в который будет вставлена склонированная фигура. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для клонирования. |

### Return Value

Ново созданный [IShape](../../ishape/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)