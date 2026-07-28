---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides dla C++ – Odwołanie API
description: Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 170
url: /pl/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metoda


Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym wstawia się ramkę Summary Zoom. |
| x | **float** | Współrzędna x nowej ramki Summary Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Summary Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Summary Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Summary Zoom, w punktach. |

### Wartość zwracana

Nowo utworzony [ISummaryZoomFrame](../../isummaryzoomframe/).
## Uwagi


Ta metoda tworzy ramkę Summary Zoom, która zbiera łącza podsumowania dla wszystkich sekcji w prezentacji. 

Ten przykład pokazuje tworzenie i wstawianie obiektu Summary Zoom w określonym indeksie kolekcji (zakładając, że w prezentacji \"Presentation.pptx\" znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomFrame](../../isummaryzoomframe/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)