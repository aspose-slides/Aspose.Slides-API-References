---
title: AddZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Zoom-ram och lägger till den i slutet av shape-samlingen.
type: docs
weight: 105
url: /sv/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metod

Skapar en ny Zoom-ram och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Den [ISlide](../../islide/) som refereras av Zoom-ramen; måste tillhöra den här presentationen. |

### Returvärde

Den nyss skapade [IZoomFrame](../../izoomframe/).

## Anmärkningar

Detta exempel visar hur man lägger till ett Zoom-objekt i slutet av en samling (anta att det finns minst två bilder i presentationen "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metod

Skapar en ny Zoom-ram och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Den [ISlide](../../islide/) som refereras av Zoom-ramen; måste tillhöra den här presentationen. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bilden för den refererade bilden [IPPImage](../../ippimage/). |

### Returvärde

Den nyss skapade [IZoomFrame](../../izoomframe/).

## Anmärkningar

Detta exempel visar hur man lägger till ett Zoom-objekt i slutet av en samling (anta att det finns minst två bilder i presentationen "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IZoomFrame](../../izoomframe/)
* Klass [ISlide](../../islide/)
* Klass [ShapeCollection](../)
* Klass [IPPImage](../../ippimage/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)