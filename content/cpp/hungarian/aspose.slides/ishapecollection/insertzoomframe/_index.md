---
title: InsertZoomFrame()
second_title: Aspose.Slides C++ API referencia
description: Új Zoom keretet hoz létre, és a megadott indexben beszúrja a shape collection-be.
type: docs
weight: 105
url: /hu/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

Létrehoz egy új Zoom keretet, és beszúrja a shape collection-be a megadott indexnél.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullaalapú index, amelynél a Zoom keretet be kell szúrni. |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A [ISlide](../../islide/), amelyre a Zoom keret hivatkozik. |

### Visszatérési érték

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).

## Megjegyzések

Ez a példa bemutatja egy Zoom objektum létrehozását és beszúrását egy gyűjtemény megadott indexén (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Létrehoz egy új Zoom keretet előre definiált képpel, és beszúrja a shape collection-be a megadott indexnél.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullaalapú index, amelynél a Zoom keretet be kell szúrni. |
| x | **float** | Az új Zoom keret x-koordinátája pontban. |
| y | **float** | Az új Zoom keret y-koordinátája pontban. |
| width | **float** | Az új Zoom keret szélessége pontban. |
| height | **float** | Az új Zoom keret magassága pontban. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | A [ISlide](../../islide/), amelyre a Zoom keret hivatkozik. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A kép a hivatkozott diára [IPPImage](../../ippimage/). |

### Visszatérési érték

Az újonnan létrehozott [IZoomFrame](../../izoomframe/).

## Megjegyzések

Ez a példa bemutatja egy Zoom objektum létrehozását és beszúrását egy gyűjtemény megadott indexén (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két dia van):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IZoomFrame](../../izoomframe/)
* Osztály [ISlide](../../islide/)
* Osztály [IShapeCollection](../)
* Osztály [IPPImage](../../ippimage/)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)