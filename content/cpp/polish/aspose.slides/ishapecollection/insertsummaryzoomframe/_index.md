---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod wskazanym indeksem.
type: docs
weight: 157
url: /pl/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metoda


Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zero-based, w którym należy wstawić ramkę Summary Zoom. |
| x | **float** | Współrzędna x nowej ramki Summary Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Summary Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Summary Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Summary Zoom, w punktach. |

### Wartość zwracana

Nowo utworzony [ISummaryZoomFrame](../../isummaryzoomframe/).

## Uwagi


Ta metoda tworzy ramkę Summary Zoom, która agreguje łącza podsumowujące dla wszystkich sekcji w prezentacji. 

Ten przykład demonstruje tworzenie i wstawianie obiektu Summary Zoom pod wskazanym indeksem kolekcji (zakładając, że w prezentacji „Presentation.pptx” znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)