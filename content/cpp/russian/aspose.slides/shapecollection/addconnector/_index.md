---
title: AddConnector()
second_title: Справочник API Aspose.Slides для C++
description: Создает новую форму соединителя с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур.
type: docs
weight: 417
url: /ru/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) метод

Создает новую форму соединителя с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) соединительной формы для добавления. |
| x | **float** | x-координата рамки соединителя, в пунктах. |
| y | **float** | y-координата рамки соединителя, в пунктах. |
| width | **float** | ширина рамки соединителя, в пунктах. |
| height | **float** | высота рамки соединителя, в пунктах. |

### Возвращаемое значение

Новый созданный [IConnector](../../iconnector/).

## Примечания

Следующий пример показывает, как добавить соединитель (изогнутый соединитель) между двумя формами (эллипсом и прямоугольником) в PowerPoint [Presentation](../../presentation/).
```cpp
// Создает экземпляр класса презентации, представляющего файл PPTX
auto input = System::MakeObject<Presentation>();

// Получает коллекцию фигур для конкретного слайда
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Добавляет автоматическую форму Эллипс
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Добавляет автоматическую форму Прямоугольник
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Добавляет форму соединителя в коллекцию фигур слайда
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Соединяет фигуры с помощью соединителя
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Вызывает Reroute, который устанавливает автоматический кратчайший путь между фигурами
connector->Reroute();

// Сохраняет презентацию
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) метод

Создает новую форму соединителя и добавляет её в конец коллекции фигур, при желании применяя оформление шаблона по умолчанию.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) соединительной формы для создания. |
| x | **float** | x-координата рамки соединителя, в пунктах. |
| y | **float** | y-координата рамки соединителя, в пунктах. |
| width | **float** | ширина рамки соединителя, в пунктах. |
| height | **float** | высота рамки соединителя, в пунктах. |
| createFromTemplate | **bool** | True, чтобы применить оформление шаблона по умолчанию (непустое имя, простой стиль); false, чтобы создать соединитель со значениями свойств по умолчанию. |

### Возвращаемое значение

Новый созданный [IConnector](../../iconnector/).

## См. также

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IConnector](../../iconnector/)
* Класс [ShapeCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)