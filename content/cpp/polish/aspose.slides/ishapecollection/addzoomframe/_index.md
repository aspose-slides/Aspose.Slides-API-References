---
title: AddZoomFrame()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 92
url: /pl/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metoda


Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Obiekt [ISlide](../../islide/) odwoływany przez ramkę Zoom; musi należeć do tej prezentacji. |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).
## Uwagi


Ten przykład pokazuje dodawanie obiektu Zoom na koniec kolekcji (zakładając, że w prezentacji \"Presentation.pptx\" znajdują się co najmniej dwa slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Obiekt [ISlide](../../islide/) odwoływany przez ramkę Zoom; musi należeć do tej prezentacji. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz dla odwoływanego slajdu [IPPImage](../../ippimage/). |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).
## Uwagi


Ten przykład pokazuje dodawanie obiektu Zoom na koniec kolekcji (zakładając, że w prezentacji \"Presentation.pptx\" znajdują się co najmniej dwa slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IZoomFrame](../../izoomframe/)
* Klasa [ISlide](../../islide/)
* Klasa [IShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)