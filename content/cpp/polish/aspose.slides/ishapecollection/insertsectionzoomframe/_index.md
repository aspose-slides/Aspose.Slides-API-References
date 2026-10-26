---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 131
url: /pl/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metoda


Tworzy nową ramkę [Section](../../section/) Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić ramkę [Section](../../section/) Zoom. |
| x | **float** | Współrzędna x nowej ramki [Section](../../section/) Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki [Section](../../section/) Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki [Section](../../section/) Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki [Section](../../section/) Zoom, w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odwołany przez ramkę [Section](../../section/) Zoom; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).
## Uwagi


Ten przykład demonstruje tworzenie i wstawianie obiektu [Section](../../section/) Zoom w określonym indeksie kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową ramkę [Section](../../section/) Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić ramkę [Section](../../section/) Zoom. |
| x | **float** | Współrzędna x nowej ramki [Section](../../section/) Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki [Section](../../section/) Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki [Section](../../section/) Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki [Section](../../section/) Zoom, w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odwołany przez ramkę [Section](../../section/) Zoom; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz wyświetlany wewnątrz ramki [Section](../../section/) Zoom. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).
## Uwagi


Ten przykład demonstruje tworzenie i wstawianie obiektu [Section](../../section/) Zoom w określonym indeksie kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISectionZoomFrame](../../isectionzoomframe/)
* Klasa [ISection](../../isection/)
* Klasa [IShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)