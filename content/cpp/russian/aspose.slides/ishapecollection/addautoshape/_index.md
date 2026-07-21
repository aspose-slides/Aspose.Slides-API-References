---
title: AddAutoShape()
second_title: Справочник API Aspose.Slides для C++
description: Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.
type: docs
weight: 313
url: /ru/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method


Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Тип [ShapeType](../../shapetype/) автофигуры, которую нужно добавить. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |

### Возвращаемое значение

Недавно созданный [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method


Создает новую автофигуру и добавляет её в конец коллекции фигур, при желании инициализируя её форматированием шаблона по умолчанию.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Тип [ShapeType](../../shapetype/) автофигуры, которую нужно добавить. |
| x | **float** | Координата x рамки фигуры, в пунктах. |
| y | **float** | Координата y рамки фигуры, в пунктах. |
| width | **float** | Ширина рамки фигуры, в пунктах. |
| height | **float** | Высота рамки фигуры, в пунктах. |
| createFromTemplate | **bool** | True, чтобы применить стиль шаблона по умолчанию (простой стиль, центрированный текст и непустое имя) к новой фигуре; false, чтобы создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |

### Возвращаемое значение

Недавно созданный [IAutoShape](../../iautoshape/).

## См. также

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)