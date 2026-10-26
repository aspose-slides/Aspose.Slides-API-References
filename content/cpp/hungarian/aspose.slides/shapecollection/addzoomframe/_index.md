---
title: AddZoomFrame()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy új Zoom képkockát, és a alakzatgyűjtemény végére adja hozzá.
type: docs
weight: 105
url: /hu/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metódus


Új Zoom képkockát hoz létre, és a alakzatgyűjtemény végére adja hozzá.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új Zoom képkocka x-koordinátája pontban. |
| y | **float** | Az új Zoom képkocka y-koordinátája pontban. |
| width | **float** | Az új Zoom képkocka szélessége pontban. |
| height | **float** | Az új Zoom képkocka magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A Zoom képkocka által hivatkozott [ISlide](../../islide/); a prezentációhoz kell tartozzon. |

### Visszatérési érték

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).

## Megjegyzés


Ez a példa azt mutatja be, hogyan lehet egy Zoom objektumot hozzáadni egy gyűjtemény végéhez (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metódus


Új Zoom képkockát hoz létre, és a alakzatgyűjtemény végére adja hozzá.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új Zoom képkocka x-koordinátája pontban. |
| y | **float** | Az új Zoom képkocka y-koordinátája pontban. |
| width | **float** | Az új Zoom képkocka szélessége pontban. |
| height | **float** | Az új Zoom képkocka magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A Zoom képkocka által hivatkozott [ISlide](../../islide/); a prezentációhoz kell tartozzon. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A hivatkozott dia [IPPImage](../../ippimage/) képe. |

### Visszatérési érték

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).

## Megjegyzés


Ez a példa azt mutatja be, hogyan lehet egy Zoom objektumot hozzáadni egy gyűjtemény végéhez (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IZoomFrame](../../izoomframe/)
* Osztály [ISlide](../../islide/)
* Osztály [ShapeCollection](../)
* Osztály [IPPImage](../../ippimage/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)