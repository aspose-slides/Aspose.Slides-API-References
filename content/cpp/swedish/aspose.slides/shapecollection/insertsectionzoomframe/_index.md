---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Section Zoom-ram och infogar den i formssamlingen på det angivna indexet.
type: docs
weight: 144
url: /sv/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

Skapar en ny [Section](../../section/) Zoom-ram och infogar den i formssamlingen på det angivna indexet.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där [Section](../../section/) Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; den måste tillhöra den här presentationen och innehålla minst en bild. |

### Return Value

Den nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks

Detta exempel visar hur man skapar och infogar ett [Section](../../section/) Zoom-objekt på det angivna indexet i en samling (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

Skapar en ny [Section](../../section/) Zoom-ram med en fördefinierad bild och infogar den i formssamlingen på det angivna indexet.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där [Section](../../section/) Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; den måste tillhöra den här presentationen och innehålla minst en bild. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bilden som ska visas i [Section](../../section/) Zoom-ramen. |

### Return Value

Den nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks

Detta exempel visar hur man skapar och infogar ett [Section](../../section/) Zoom-objekt på det angivna indexet i en samling (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)