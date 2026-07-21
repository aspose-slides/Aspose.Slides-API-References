---
title: AddGroupShape()
second_title: Aspose.Slides для C++ справочник API
description: Создает новую пустую группу фигур и добавляет её в конец коллекции фигур. Кадр группы будет автоматически подстраиваться под любые добавленные в неё фигуры.
type: docs
weight: 352
url: /ru/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() метод


Создает новую пустую группу фигур и добавляет её в конец коллекции фигур. Кадр группы будет автоматически подстраиваться под любые фигуры, добавленные в него.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Возвращаемое значение

Новосозданный [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) метод


Создает новую группу фигур, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) содержащий векторное содержимое для преобразования в фигуры. |
| x | **float** | Координата x кадра группы, в пунктах. |
| y | **float** | Координата y кадра группы, в пунктах. |
| width | **float** | Ширина кадра группы, в пунктах. |
| height | **float** | Высота кадра группы, в пунктах. |

### Возвращаемое значение

Новосозданный [IGroupShape](../../igroupshape/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IGroupShape](../../igroupshape/)
* Класс [IShapeCollection](../)
* Класс [ISvgImage](../../isvgimage/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)