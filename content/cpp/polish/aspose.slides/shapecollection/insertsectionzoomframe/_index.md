---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów w podanym indeksie.
type: docs
weight: 144
url: /pl/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metoda


Tworzy nową [Section](../../section/) Zoom ramkę i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić [Section](../../section/) Zoom ramkę. |
| x | **float** | Współrzędna x nowej [Section](../../section/) Zoom ramki, w punktach. |
| y | **float** | Współrzędna y nowej [Section](../../section/) Zoom ramki, w punktach. |
| width | **float** | Szerokość nowej [Section](../../section/) Zoom ramki, w punktach. |
| height | **float** | Wysokość nowej [Section](../../section/) Zoom ramki, w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odwoływany przez [Section](../../section/) Zoom ramkę; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).

## Uwagi


Ten przykład demonstruje tworzenie i wstawianie obiektu [Section](../../section/) Zoom w określonym indeksie kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową [Section](../../section/) Zoom ramkę z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić [Section](../../section/) Zoom ramkę. |
| x | **float** | Współrzędna x nowej [Section](../../section/) Zoom ramki, w punktach. |
| y | **float** | Współrzędna y nowej [Section](../../section/) Zoom ramki, w punktach. |
| width | **float** | Szerokość nowej [Section](../../section/) Zoom ramki, w punktach. |
| height | **float** | Wysokość nowej [Section](../../section/) Zoom ramki, w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) odwoływany przez [Section](../../section/) Zoom ramkę; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz wyświetlany wewnątrz [Section](../../section/) Zoom ramki. |

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


## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISectionZoomFrame](../../isectionzoomframe/)
* Klasa [ISection](../../isection/)
* Klasa [ShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)