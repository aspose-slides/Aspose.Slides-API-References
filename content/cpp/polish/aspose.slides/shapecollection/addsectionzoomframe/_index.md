---
title: AddSectionZoomFrame()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową ramkę Section Zoom i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 131
url: /pl/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metoda


Tworzy nową [Section](../../section/) Zoom frame i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| y | **float** | Współrzędna y nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| width | **float** | Szerokość nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| height | **float** | Wysokość nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odwołujący się do [Section](../../section/) Zoom frame; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).
## Uwagi


Ten przykład demonstruje dodawanie obiektu [Section](../../section/) Zoom na koniec kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajdują się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową [Section](../../section/) Zoom frame z wstępnie określonym obrazem i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| y | **float** | Współrzędna y nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| width | **float** | Szerokość nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| height | **float** | Wysokość nowej [Section](../../section/) Zoom frame, wyrażona w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odwołujący się do [Section](../../section/) Zoom frame; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) wyświetlany w [Section](../../section/) Zoom frame. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).
## Uwagi


Ten przykład demonstruje dodawanie obiektu [Section](../../section/) Zoom na koniec kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajdują się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISectionZoomFrame](../../isectionzoomframe/)
* Klasa [ISection](../../isection/)
* Klasa [ShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)