---
title: InsertZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 105
url: /sv/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) metod


Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) som refereras av Zoom-ramen. |

### Returvärde

Det nyss skapade [IZoomFrame](../../izoomframe/).
## Anmärkningar


Detta exempel demonstrerar skapande och infogning av ett Zoom-objekt på det angivna indexet i en samling (anta att presentationen \"Presentation.pptx\" innehåller minst två bilder): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metod


Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) som refereras av Zoom-ramen. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bilden för den refererade bilden [IPPImage](../../ippimage/). |

### Returvärde

Det nyss skapade [IZoomFrame](../../izoomframe/).
## Anmärkningar


Detta exempel demonstrerar skapande och infogning av ett Zoom-objekt på det angivna indexet i en samling (anta att presentationen \"Presentation.pptx\" innehåller minst två bilder): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IZoomFrame](../../izoomframe/)
* Klass [ISlide](../../islide/)
* Klass [IShapeCollection](../)
* Klass [IPPImage](../../ippimage/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)