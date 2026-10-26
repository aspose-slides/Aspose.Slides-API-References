---
title: InsertConnector()
second_title: Aspose.Slides для C++ справочник API
description: Создает новую форму-connector и вставляет её в коллекцию фигур по указанному индексу, применяя стиль шаблона по умолчанию.
type: docs
weight: 430
url: /ru/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) метод

Создает новую форму-соединитель и вставляет её в коллекцию фигур по указанному индексу, применяя стиль шаблона по умолчанию.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому будет вставлена форма-соединитель. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) формы-соединителя для вставки. |
| x | **float** | Координата x кадра соединителя, в пунктах. |
| y | **float** | Координата y кадра соединителя, в пунктах. |
| width | **float** | Ширина кадра соединителя, в пунктах. |
| height | **float** | Высота кадра соединителя, в пунктах. |

### Возвращаемое значение

Новосозданный [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) метод

Создает новую форму-соединитель и вставляет её в коллекцию фигур по указанному индексу, при необходимости применяя стиль шаблона по умолчанию.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому будет вставлена форма-соединитель. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) формы-соединителя для вставки. |
| x | **float** | Координата x кадра соединителя, в пунктах. |
| y | **float** | Координата y кадра соединителя, в пунктах. |
| width | **float** | Ширина кадра соединителя, в пунктах. |
| height | **float** | Высота кадра соединителя, в пунктах. |
| createFromTemplate | **bool** | True, если нужно применить стиль шаблона по умолчанию (непустое имя, простой стиль); false, если создать соединитель со значениями свойств по умолчанию. |

### Возвращаемое значение

Новосозданный [IConnector](../../iconnector/).

## См. также

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)