---
title: AddZoomFrame()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 105
url: /pl/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metoda


Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odwoływany przez ramkę Zoom; musi należeć do tej prezentacji. |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).

## Uwagi


Ten przykład demonstruje dodawanie obiektu Zoom na koniec kolekcji (zakładamy, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) odwoływany przez ramkę Zoom; musi należeć do tej prezentacji. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz dla odwoływanego slajdu [IPPImage](../../ippimage/). |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).

## Uwagi


Ten przykład demonstruje dodawanie obiektu Zoom na koniec kolekcji (zakładamy, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)