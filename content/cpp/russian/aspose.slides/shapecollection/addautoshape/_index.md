---
title: AddAutoShape()
second_title: Справочник API Aspose.Slides для C++
description: Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.
type: docs
weight: 352
url: /ru/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) метод

Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Значение [ShapeType](../../shapetype/) автофигуры для добавления. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |

### Return Value

Новосозданный [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) метод

Создает новую автофигуру и добавляет её в конец коллекции фигур, при желании инициализируя её форматированием шаблона по умолчанию.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Значение [ShapeType](../../shapetype/) автофигуры для добавления. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |
| createFromTemplate | **bool** | true — применить стиль шаблона по умолчанию (простой стиль, центрированный текст и непустое имя) к новой фигуре; false — создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |

### Return Value

Новосозданный [IAutoShape](../../iautoshape/).

## See Also

* Перечисление [ShapeType](../../shapetype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [ShapeCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)