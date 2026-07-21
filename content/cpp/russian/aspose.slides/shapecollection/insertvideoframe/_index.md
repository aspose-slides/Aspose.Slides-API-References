---
title: InsertVideoFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый видеокадр и вставляет его в коллекцию фигур в указанном индексе.
type: docs
weight: 222
url: /ru/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) метод

Создаёт новый видеокадр и вставляет его в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевая позиция индекса, в которой следует вставить видеокадр. |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| fname | [System::String](../../../system/string/) | Путь или имя видеофайла для встраивания. |

### Возвращаемое значение

Созданный [IVideoFrame](../../ivideoframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IVideoFrame](../../ivideoframe/)
* Класс [String](../../../system/string/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)