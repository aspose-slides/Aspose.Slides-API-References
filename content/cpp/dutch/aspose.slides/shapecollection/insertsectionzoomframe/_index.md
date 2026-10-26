---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw Section Zoom-frame en voegt het in de shape-collectie in op de opgegeven index.
type: docs
weight: 144
url: /nl/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) methode


Maakt een nieuw [Section](../../section/) Zoom-frame en voegt het in de shape-collectie in op de opgegeven index.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het [Section](../../section/) Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | De [ISection](../../isection/) waarnaar verwezen wordt door het [Section](../../section/) Zoom-frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |

### Retourwaarde

Het nieuw aangemaakte [ISectionZoomFrame](../../isectionzoomframe/).

## Opmerkingen


Dit voorbeeld toont de creatie en invoeging van een [Section](../../section/) Zoom-object op de opgegeven index van een collectie (ga uit van minstens twee secties in de "Presentation.pptx"-presentatie): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) methode


Maakt een nieuw [Section](../../section/) Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de shape-collectie in op de opgegeven index.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het [Section](../../section/) Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe [Section](../../section/) Zoom-frame, in punten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | De [ISection](../../isection/) waarnaar verwezen wordt door het [Section](../../section/) Zoom-frame; moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De afbeelding die wordt weergegeven in het [Section](../../section/) Zoom-frame. |

### Retourwaarde

Het nieuw aangemaakte [ISectionZoomFrame](../../isectionzoomframe/).

## Opmerkingen


Dit voorbeeld toont de creatie en invoeging van een [Section](../../section/) Zoom-object op de opgegeven index van een collectie (ga uit van minstens twee secties in de "Presentation.pptx"-presentatie): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISectionZoomFrame](../../isectionzoomframe/)
* Klasse [ISection](../../isection/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)