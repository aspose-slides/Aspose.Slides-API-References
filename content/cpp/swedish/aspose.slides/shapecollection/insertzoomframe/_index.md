---
title: InsertZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 118
url: /sv/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method


Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Den [ISlide](../../islide/) som Zoom-ramen refererar till. |

### Return Value

Det nyss skapade [IZoomFrame](../../izoomframe/).
## Remarks


Detta exempel visar hur man skapar och infogar ett Zoom-objekt på det angivna indexet i en samling (anta att det finns minst två bilder i presentationen "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method


Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Den [ISlide](../../islide/) som Zoom-ramen refererar till. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bilden för den refererade bilden [IPPImage](../../ippimage/). |

### Return Value

Det nyss skapade [IZoomFrame](../../izoomframe/).
## Remarks


Detta exempel visar hur man skapar och infogar ett Zoom-objekt på det angivna indexet i en samling (anta att det finns minst två bilder i presentationen "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)