---
title: AddVideoFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый видеокадр и добавляет его в конец коллекции фигур.
type: docs
weight: 170
url: /ru/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) метод

Создаёт новый видеокадр и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| fname | [System::String](../../../system/string/) | Путь или имя видеофайла для встраивания. |

### Return Value

Созданный только что [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) метод

Создаёт новый видеокадр и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового видеокадра, в пунктах. |
| y | **float** | Координата y нового видеокадра, в пунктах. |
| width | **float** | Ширина нового видеокадра, в пунктах. |
| height | **float** | Высота нового видеокадра, в пунктах. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Объект [IVideo](../../ivideo/) для встраивания в видеокадр. |

### Return Value

Созданный только что [IVideoFrame](../../ivideoframe/).

## See Also

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IVideoFrame](../../ivideoframe/)
* Класс [String](../../../system/string/)
* Класс [IShapeCollection](../)
* Класс [IVideo](../../ivideo/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)