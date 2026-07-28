---
title: AddSectionZoomFrame()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową ramkę Zoom sekcji i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 118
url: /pl/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metoda

Tworzy nową [Section](../../section/) ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| y | **float** | Współrzędna y nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| width | **float** | Szerokość nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| height | **float** | Wysokość nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Sekcja [ISection](../../isection/) odwołująca się do ramki [Section](../../section/) Zoom; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).

## Uwagi

Ten przykład demonstruje dodanie obiektu Zoom [Section](../../section/) na koniec kolekcji (przyjmując, że w prezentacji „Presentation.pptx” znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metoda

Tworzy nową ramkę [Section](../../section/) Zoom z predefiniowanym obrazem i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| y | **float** | Współrzędna y nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| width | **float** | Szerokość nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| height | **float** | Wysokość nowej ramki [Section](../../section/) Zoom, wyrażona w punktach. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Sekcja [ISection](../../isection/) odwołująca się do ramki [Section](../../section/) Zoom; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz [IPPImage](../../ippimage/) wyświetlany w ramce [Section](../../section/) Zoom. |

### Wartość zwracana

Nowo utworzony [ISectionZoomFrame](../../isectionzoomframe/).

## Uwagi

Ten przykład demonstruje dodanie obiektu Zoom [Section](../../section/) na koniec kolekcji (przyjmując, że w prezentacji „Presentation.pptx” znajduje się co najmniej dwie sekcje): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISectionZoomFrame](../../isectionzoomframe/)
* Klasa [ISection](../../isection/)
* Klasa [IShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)