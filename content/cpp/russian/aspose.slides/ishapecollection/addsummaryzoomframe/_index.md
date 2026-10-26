---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый кадр Summary Zoom и добавляет его в конец коллекции фигур.
type: docs
weight: 144
url: /ru/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) method

Создает новый кадр Summary Zoom и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового кадра Summary Zoom, в пунктах. |
| y | **float** | Координата y нового кадра Summary Zoom, в пунктах. |
| width | **float** | Ширина нового кадра Summary Zoom, в пунктах. |
| height | **float** | Высота нового кадра Summary Zoom, в пунктах. |

### Return Value

Созданный [ISummaryZoomFrame](../../isummaryzoomframe/).

## Remarks

Этот метод создает кадр Summary Zoom, который собирает ссылки-резюме для всех разделов презентации. 

Этот пример демонстрирует добавление объекта Summary Zoom в конец коллекции (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISummaryZoomFrame](../../isummaryzoomframe/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)