---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 157
url: /pl/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) method

Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
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

## Uwagi

Ta metoda tworzy nowe Summary Zoom i umieszcza w nim kolekcję obiektów dla wszystkich sekcji w tej prezentacji.

Ten przykład demonstruje dodawanie obiektu Summary Zoom na koniec kolekcji (załóżmy, że w prezentacji „Presentation.pptx” jest co najmniej dwie sekcje):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)