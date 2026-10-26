---
title: InsertConnector()
second_title: Справочник API Aspose.Slides for C++
description: Создает новую фигуру-соединитель и вставляет её в коллекцию фигур по указанному индексу, применяя стиль шаблона по умолчанию.
type: docs
weight: 391
url: /ru/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) метод

Создает новую форму-соединитель и вставляет её в коллекцию фигур по указанному индексу, применяя стиль шаблона по умолчанию.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой (отсчет с нуля) индекс, по которому вставляется форма-соединитель. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) формы-соединителя, которую нужно вставить. |
| x | **float** | Координата x кадра соединителя, в пунктах. |
| y | **float** | Координата y кадра соединителя, в пунктах. |
| width | **float** | Ширина кадра соединителя, в пунктах. |
| height | **float** | Высота кадра соединителя, в пунктах. |

### Возвращаемое значение

Новая созданная [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) метод

Создает новую форму-соединитель и вставляет её в коллекцию фигур по указанному индексу, при необходимости применяя стиль шаблона по умолчанию.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой (отсчет с нуля) индекс, по которому вставляется форма-соединитель. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) формы-соединителя, которую нужно вставить. |
| x | **float** | Координата x кадра соединителя, в пунктах. |
| y | **float** | Координата y кадра соединителя, в пунктах. |
| width | **float** | Ширина кадра соединителя, в пунктах. |
| height | **float** | Высота кадра соединителя, в пунктах. |
| createFromTemplate | **bool** | True, чтобы применить стиль шаблона по умолчанию (непустое имя, простой стиль); false, чтобы создать соединитель со значениями свойств по умолчанию. |

### Возвращаемое значение

Новая созданная [IConnector](../../iconnector/).

## См. также

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)