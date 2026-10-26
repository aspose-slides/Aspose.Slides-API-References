---
title: InsertVideoFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый видеокадр и вставляет его в коллекцию фигур в указанном индексе.
type: docs
weight: 183
url: /ru/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) метод

Создает новый видеокадр и вставляет его в коллекцию фигур в указанном индексе.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором следует вставить видеокадр. |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| fname | [System::String](../../../system/string/) | Путь или имя видеофайла для встраивания. |

### Возвращаемое значение

Новый созданный [IVideoFrame](../../ivideoframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IVideoFrame](../../ivideoframe/)
* Класс [String](../../../system/string/)
* Класс [IShapeCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)