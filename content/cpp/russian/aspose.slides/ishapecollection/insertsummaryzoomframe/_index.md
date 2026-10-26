---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides для C++ API справка
description: Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 157
url: /ru/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) метод


Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому следует вставить кадр Summary Zoom. |
| x | **float** | Координата x нового кадра Summary Zoom в пунктах. |
| y | **float** | Координата y нового кадра Summary Zoom в пунктах. |
| width | **float** | Ширина нового кадра Summary Zoom в пунктах. |
| height | **float** | Высота нового кадра Summary Zoom в пунктах. |

### Возвращаемое значение

Созданный только что [ISummaryZoomFrame](../../isummaryzoomframe/).
## Примечания


Этот метод создает кадр Summary Zoom, который агрегирует ссылки-резюме для всех разделов презентации. 

Этот пример демонстрирует создание и вставку объекта Summary Zoom в указанный индекс коллекции (предположим, что в презентации "Presentation.pptx" хотя бы два раздела): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomFrame](../../isummaryzoomframe/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)