---
title: AddSummaryZoomFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый кадр Summary Zoom и добавляет его в конец коллекции фигур.
type: docs
weight: 157
url: /ru/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) метод

Создаёт новый кадр Summary Zoom и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового кадра Summary Zoom в пунктах. |
| y | **float** | Координата y нового кадра Summary Zoom в пунктах. |
| width | **float** | Ширина нового кадра Summary Zoom в пунктах. |
| height | **float** | Высота нового кадра Summary Zoom в пунктах. |

### Возвращаемое значение

Созданный [ISummaryZoomFrame](../../isummaryzoomframe/).

## Примечания

Этот метод создаёт новый Summary Zoom и помещает в него коллекцию объектов для всех секций этой презентации.

В этом примере демонстрируется добавление объекта Summary Zoom в конец коллекции (предполагается, что в презентации «Presentation.pptx» присутствует как минимум две секции):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomFrame](../../isummaryzoomframe/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)