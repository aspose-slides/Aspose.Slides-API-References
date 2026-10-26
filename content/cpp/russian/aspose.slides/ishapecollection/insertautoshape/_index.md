---
title: InsertAutoShape()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, применяя форматирование шаблона по умолчанию.
type: docs
weight: 339
url: /ru/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, применяя форматирование шаблона по умолчанию.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором следует вставить новую автофигуру. |
| shapeType | [ShapeType](../../shapetype/) | Значение [ShapeType](../../shapetype/) автофигуры, которую необходимо вставить. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |

### Return Value

Созданный [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, при необходимости инициализируя её стилем шаблона по умолчанию.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором следует вставить автофигуру. |
| shapeType | [ShapeType](../../shapetype/) | Значение [ShapeType](../../shapetype/) автофигуры, которую необходимо вставить. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |
| createFromTemplate | **bool** | True to apply default template styling (including a non-empty name, simple style, and centered text); false to create the shape with all properties set to their defaults. |

### Return Value

Созданный [IAutoShape](../../iautoshape/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)