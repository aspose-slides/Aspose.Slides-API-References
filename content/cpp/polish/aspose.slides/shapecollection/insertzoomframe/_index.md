---
title: InsertZoomFrame()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 118
url: /pl/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) metoda


Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona ramka Zoom. |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odwołany przez ramkę Zoom. |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).
## Uwagi


Ten przykład demonstruje tworzenie i wstawianie obiektu Zoom pod określonym indeksem w kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona ramka Zoom. |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odwołany przez ramkę Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz dla odwołanego slajdu [IPPImage](../../ippimage/). |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).
## Uwagi


Ten przykład demonstruje tworzenie i wstawianie obiektu Zoom pod określonym indeksem w kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IZoomFrame](../../izoomframe/)
* Klasa [ISlide](../../islide/)
* Klasa [ShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)