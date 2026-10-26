---
title: AddControl()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт и добавляет новый элемент управления в коллекцию.
type: docs
weight: 40
url: /ru/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) метод

Создаёт и добавляет новый элемент управления в коллекцию.

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | Тип элемента управления, который нужно добавить. |
| x | **float** | Координата X левой стороны рамки фигуры. |
| y | **float** | Координата Y верхней стороны рамки фигуры. |
| width | **float** | Ширина рамки фигуры. |
| height | **float** | Высота рамки фигуры. |

### Возвращаемое значение

Созданный элемент управления.

## См. также

* Перечисление [ControlType](../../controltype/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IControl](../../icontrol/)
* Класс [ControlCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)