---
title: AddSectionZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Section Zoom frame en voegt het toe aan het einde van de shape collection.
type: docs
weight: 131
url: /nl/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) methode


Maakt een nieuw [Section](../../section/) Zoom frame en voegt het toe aan het einde van de vormverzameling.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Het [ISection](../../isection/) waarnaar verwezen wordt door het [Section](../../section/) Zoom frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |

### Retourwaarde

De nieuw aangemaakte [ISectionZoomFrame](../../isectionzoomframe/).

## Opmerkingen


Dit voorbeeld toont het toevoegen van een [Section](../../section/) Zoom object aan het einde van een collectie (ga uit van ten minste twee secties in de "Presentation.pptx" presentatie): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) methode


Maakt een nieuw [Section](../../section/) Zoom frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe [Section](../../section/) Zoom frame, in punten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Het [ISection](../../isection/) waarnaar verwezen wordt door het [Section](../../section/) Zoom frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De [IPPImage](../../ippimage/) die weergegeven moet worden binnen het [Section](../../section/) Zoom frame. |

### Retourwaarde

De nieuw aangemaakte [ISectionZoomFrame](../../isectionzoomframe/).

## Opmerkingen


Dit voorbeeld toont het toevoegen van een [Section](../../section/) Zoom object aan het einde van een collectie (ga uit van ten minste twee secties in de "Presentation.pptx" presentatie): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISectionZoomFrame](../../isectionzoomframe/)
* Klasse [ISection](../../isection/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)