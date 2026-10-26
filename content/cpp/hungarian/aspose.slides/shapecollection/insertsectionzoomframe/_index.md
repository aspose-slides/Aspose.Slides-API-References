---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides C++ API Referencia
description: Új Section Zoom keretet hoz létre, és a megadott indexnél beszúrja a forma gyűjteménybe.
type: docs
weight: 144
url: /hu/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metódus


Létrehoz egy új [Section](../../section/) Zoom keretet, és a megadott indexnél beszúrja a forma gyűjteménybe.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától kezdődő index, ahol a [Section](../../section/) Zoom keretet be kell szúrni. |
| x | **float** | Az új [Section](../../section/) Zoom keret x-koordinátája pontban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y-koordinátája pontban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége pontban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága pontban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | A [Section](../../section/) Zoom keret által hivatkozott [ISection](../../isection/); a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések


Ez a példa bemutatja egy [Section](../../section/) Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexére (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metódus


Létrehoz egy új [Section](../../section/) Zoom keretet előre definiált képpel, és a megadott indexnél beszúrja a forma gyűjteménybe.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától kezdődő index, ahol a [Section](../../section/) Zoom keretet be kell szúrni. |
| x | **float** | Az új [Section](../../section/) Zoom keret x-koordinátája pontban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y-koordinátája pontban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége pontban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága pontban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | A [Section](../../section/) Zoom keret által hivatkozott [ISection](../../isection/); a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A [Section](../../section/) Zoom keretben megjelenítendő kép. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések


Ez a példa bemutatja egy [Section](../../section/) Zoom objektum létrehozását és beszúrását a gyűjtemény megadott indexére (feltételezve, hogy a "Presentation.pptx" prezentációban legalább két szakasz van): 
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
* Osztály [ShapeCollection](../)
* Osztály [IPPImage](../../ippimage/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)