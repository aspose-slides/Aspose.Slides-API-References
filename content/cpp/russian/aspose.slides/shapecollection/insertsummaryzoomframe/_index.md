---
title: InsertSummaryZoomFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 170
url: /ru/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) метод

Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому следует вставить кадр Summary Zoom. |
| x | **float** | Координата x нового кадра Summary Zoom в пунктах. |
| y | **float** | Координата y нового кадра Summary Zoom в пунктах. |
| width | **float** | Ширина нового кадра Summary Zoom в пунктах. |
| height | **float** | Высота нового кадра Summary Zoom в пунктах. |

### Return Value

Новосозданный [ISummaryZoomFrame](../../isummaryzoomframe/).

## Remarks

Этот метод создает кадр Summary Zoom, который агрегирует ссылки-резюме для всех разделов в презентации.

Этот пример демонстрирует создание и вставку объекта Summary Zoom по указанному индексу в коллекцию (предположим, что в презентации "Presentation.pptx" как минимум два раздела):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomFrame](../../isummaryzoomframe/)
* Класс [ShapeCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)