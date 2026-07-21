---
title: AddVideoFrame()
second_title: Aspose.Slides для справочника API C++
description: Создает новый видеокадр и добавляет его в конец коллекции фигур.
type: docs
weight: 209
url: /ru/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) метод

Создает новый видеокадр и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| fname | [System::String](../../../system/string/) | Путь или имя видеофайла для встраивания. |

### Возвращаемое значение

Созданный только что [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) метод

Создает новый видеокадр и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Объект [IVideo](../../ivideo/) для встраивания в видеокадр. |

### Возвращаемое значение

Созданный только что [IVideoFrame](../../ivideoframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Class [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)