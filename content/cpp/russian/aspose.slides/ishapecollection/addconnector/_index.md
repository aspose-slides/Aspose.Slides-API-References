---
title: AddConnector()
second_title: Aspose.Slides для C++ справочник API
description: Создает новую соединительную фигуру со стилем шаблона по умолчанию и добавляет её в конец коллекции фигур.
type: docs
weight: 378
url: /ru/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) метод


Создает новую соединительную фигуру со стилем шаблона по умолчанию и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) соединительной фигуры для добавления. |
| x | **float** | Координата x кадра соединителя, в пунктах. |
| y | **float** | Координата y кадра соединителя, в пунктах. |
| width | **float** | Ширина кадра соединителя, в пунктах. |
| height | **float** | Высота кадра соединителя, в пунктах. |

### Возвращаемое значение

Созданный [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) метод


Создает новую соединительную фигуру и добавляет её в конец коллекции фигур, при необходимости применяя стиль шаблона по умолчанию.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) соединительной фигуры для создания. |
| x | **float** | Координата x кадра соединителя, в пунктах. |
| y | **float** | Координата y кадра соединителя, в пунктах. |
| width | **float** | Ширина кадра соединителя, в пунктах. |
| height | **float** | Высота кадра соединителя, в пунктах. |
| createFromTemplate | **bool** | True, если необходимо применить стиль шаблона по умолчанию (непустое имя, простой стиль); false, если нужно создать соединитель со значениями свойств по умолчанию. |

### Возвращаемое значение

Созданный [IConnector](../../iconnector/).

## См. также

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IConnector](../../iconnector/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)