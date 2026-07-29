---
title: AddSectionZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Section Zoom-ram och lägger till den i slutet av formsamlingen.
type: docs
weight: 131
url: /sv/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method


Skapar en ny [Section](../../section/) Zoom-ram och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Den [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; måste tillhöra denna presentation och innehålla minst en bild. |

### Return Value

Den nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks


Detta exempel visar hur man lägger till ett [Section](../../section/) Zoom-objekt i slutet av en samling (anta att det finns minst två sektioner i presentationen "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Skapar en ny [Section](../../section/) Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Den [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; måste tillhöra denna presentation och innehålla minst en bild. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Den [IPPImage](../../ippimage/) som ska visas i [Section](../../section/) Zoom-ramen. |

### Return Value

Den nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks


Detta exempel visar hur man lägger till ett [Section](../../section/) Zoom-objekt i slutet av en samling (anta att det finns minst två sektioner i presentationen "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)