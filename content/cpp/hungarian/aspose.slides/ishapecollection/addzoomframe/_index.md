---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API Referencia
description: Új Zoom keretet hoz létre, és az alakzatgyűjtemény végéhez adja hozzá.
type: docs
weight: 92
url: /hu/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) módszer


Creates a new Zoom frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A Zoom keret által hivatkozott [ISlide](../../islide/); a prezentációnak kell, hogy tartozzon. |

### Return Value

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).
## Remarks


Ez a példa bemutatja egy Zoom objektum hozzáadását egy gyűjtemény végéhez (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) módszer


Creates a new Zoom frame and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A Zoom keret által hivatkozott [ISlide](../../islide/); a prezentációnak kell, hogy tartozzon. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A hivatkozott dia [IPPImage](../../ippimage/) képe. |

### Return Value

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).
## Remarks


Ez a példa bemutatja egy Zoom objektum hozzáadását egy gyűjtemény végéhez (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)