---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides C++ API-referencia
description: Új Section Zoom keretet hoz létre, és a megadott indexnél beszúrja a formagyűjteménybe.
type: docs
weight: 131
url: /hu/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metódus


Új [Section](../../section/) Zoom keretet hoz létre, és beszúrja a formagyűjteménybe a megadott indexen.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nulláralapú index, amelynél a [Section](../../section/) Zoom keretet be kell szúrni. |
| x | **float** | Az új [Section](../../section/) Zoom keret x koordinátája pontban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y koordinátája pontban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége pontban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága pontban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) amelyet a [Section](../../section/) Zoom keret hivatkozik; a bemutatóhoz kell tartozzon és legalább egy diát kell tartalmazzon. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések


Ez a példa bemutatja egy [Section](../../section/) Zoom objektum létrehozását és beszúrását egy gyűjtemény meghatározott indexére (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szakasz van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metódus


Új [Section](../../section/) Zoom keretet hoz létre előre definiált képpel, és beszúrja a formagyűjteménybe a megadott indexen.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nulláralapú index, amelynél a [Section](../../section/) Zoom keretet be kell szúrni. |
| x | **float** | Az új [Section](../../section/) Zoom keret x koordinátája pontban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y koordinátája pontban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége pontban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága pontban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) amelyet a [Section](../../section/) Zoom keret hivatkozik; a bemutatóhoz kell tartozzon és legalább egy diát kell tartalmazzon. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A [Section](../../section/) Zoom kereten belül megjelenítendő kép. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések


Ez a példa bemutatja egy [Section](../../section/) Zoom objektum létrehozását és beszúrását egy gyűjtemény meghatározott indexére (feltételezve, hogy a "Presentation.pptx" bemutatóban legalább két szakasz van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISectionZoomFrame](../../isectionzoomframe/)
* Osztály [ISection](../../isection/)
* Osztály [IShapeCollection](../)
* Osztály [IPPImage](../../ippimage/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)