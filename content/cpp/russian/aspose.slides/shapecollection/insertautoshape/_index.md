---
title: InsertAutoShape()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новую автоформу и вставляет её в коллекцию форм по указанному индексу, применяя форматирование шаблона по умолчанию.
type: docs
weight: 378
url: /ru/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

Создаёт новую автоформу и вставляет её в коллекцию форм по указанному индексу, применяя форматирование шаблона по умолчанию.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ноль-based индекс, по которому вставлять новую автоформу. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) автоформы для вставки. |
| x | **float** | Координата x фрейма формы, в пунктах. |
| y | **float** | Координата y фрейма формы, в пунктах. |
| width | **float** | Ширина фрейма формы, в пунктах. |
| height | **float** | Высота фрейма формы, в пунктах. |

### Return Value

Новосозданный [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

Создаёт новую автоформу и вставляет её в коллекцию форм по указанному индексу, опционально инициализируя её стилем шаблона по умолчанию.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ноль-based индекс, по которому вставлять форму. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) автоформы для вставки. |
| x | **float** | Координата x фрейма формы, в пунктах. |
| y | **float** | Координата y фрейма формы, в пунктах. |
| width | **float** | Ширина фрейма формы, в пунктах. |
| height | **float** | Высота фрейма формы, в пунктах. |
| createFromTemplate | **bool** | True, чтобы применить стиль шаблона по умолчанию (включая непустое имя, простой стиль и центрированный текст); false, чтобы создать форму со всеми свойствами, установленными в их значения по умолчанию. |

### Return Value

Новосозданный [IAutoShape](../../iautoshape/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)