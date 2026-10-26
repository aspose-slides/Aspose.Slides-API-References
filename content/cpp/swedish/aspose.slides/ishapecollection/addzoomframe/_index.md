---
title: AddZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.
type: docs
weight: 92
url: /sv/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metod


Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Det [ISlide](../../islide/) som refereras av Zoom-ramen; måste tillhöra denna presentation. |

### Returvärde

Den nyss skapade [IZoomFrame](../../izoomframe/).
## Anmärkningar


Detta exempel demonstrerar hur man lägger till ett Zoom-objekt i slutet av en samling (anta att det finns minst två bilder i presentationen \"Presentation.pptx\"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metod


Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Zoom-ramen, i punkter. |
| width | **float** | bredden på den nya Zoom-ramen, i punkter. |
| height | **float** | höjden på den nya Zoom-ramen, i punkter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Det [ISlide](../../islide/) som refereras av Zoom-ramen; måste tillhöra denna presentation. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bilden för den refererade bilden [IPPImage](../../ippimage/). |

### Returvärde

Den nyss skapade [IZoomFrame](../../izoomframe/).
## Anmärkningar


Detta exempel demonstrerar hur man lägger till ett Zoom-objekt i slutet av en samling (anta att det finns minst två bilder i presentationen \"Presentation.pptx\"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)