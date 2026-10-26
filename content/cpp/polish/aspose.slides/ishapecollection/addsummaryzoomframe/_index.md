---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 144
url: /pl/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) method

Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki Summary Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Summary Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Summary Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Summary Zoom, w punktach. |

### Wartość zwracana

Nowo utworzony [ISummaryZoomFrame](../../isummaryzoomframe/).
## Uwaga

Ta metoda tworzy ramkę Summary Zoom, która agreguje linki podsumowujące dla wszystkich sekcji w prezentacji. 

Ten przykład pokazuje, jak dodać obiekt Summary Zoom na koniec kolekcji (zakładając, że w prezentacji „Presentation.pptx” znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)