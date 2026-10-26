---
title: InsertZoomFrame()
second_title: Aspose.Slides C++ API referencia
description: Új Zoom keretet hoz létre, és a megadott indexnél beszúrja a formagyűjteménybe.
type: docs
weight: 118
url: /hu/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) metódus


Új Zoom keretet hoz létre, és beszúrja a formagyűjteménybe a megadott indexnél.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulláktól kezdődő index, ahová a Zoom keretet be kell szúrni. |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A Zoom keret által hivatkozott [ISlide](../../islide/). |

### Visszatérési érték

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).
## Megjegyzés


Ez a példa bemutatja egy Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén (feltételezve, hogy a \"Presentation.pptx\" prezentációban legalább két dia van): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metódus


Új Zoom keretet hoz létre előre definiált képpel, és beszúrja a formagyűjteménybe a megadott indexnél.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulláktól kezdődő index, ahová a Zoom keretet be kell szúrni. |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A Zoom keret által hivatkozott [ISlide](../../islide/). |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A [IPPImage](../../ippimage/) hivatkozott dia képe. |

### Visszatérési érték

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).
## Megjegyzés


Ez a példa bemutatja egy Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexén (feltételezve, hogy a \"Presentation.pptx\" prezentációban legalább két dia van): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IZoomFrame](../../izoomframe/)
* Osztály [ISlide](../../islide/)
* Osztály [ShapeCollection](../)
* Osztály [IPPImage](../../ippimage/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)