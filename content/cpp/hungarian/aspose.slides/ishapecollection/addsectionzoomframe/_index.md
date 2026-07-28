---
title: AddSectionZoomFrame()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy új Section Zoom keretet, és hozzáadja a shape collection végéhez.
type: docs
weight: 118
url: /hu/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metódus

Létrehoz egy új [Section](../../section/) Zoom keretet, és hozzáadja a alakzatgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új [Section](../../section/) Zoom keret x-koordinátája pontban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y-koordinátája pontban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége pontban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága pontban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | A [ISection](../../isection/) amelyre a [Section](../../section/) Zoom keret hivatkozik; a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések

Ez a példa bemutatja egy [Section](../../section/) Zoom objektum hozzáadását a gyűjtemény végéhez (tételezzük fel, hogy a "Presentation.pptx" prezentációban legalább két szekció van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metódus

Létrehoz egy új [Section](../../section/) Zoom keretet egy előre meghatározott képpel, és hozzáadja a alakzatgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új [Section](../../section/) Zoom keret x-koordinátája pontban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y-koordinátája pontban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége pontban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága pontban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | A [ISection](../../isection/) amelyre a [Section](../../section/) Zoom keret hivatkozik; a prezentációnak kell tartoznia, és legalább egy diát kell tartalmaznia. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A [IPPImage](../../ippimage/) amely a [Section](../../section/) Zoom keretben jelenik meg. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések

Ez a példa bemutatja egy [Section](../../section/) Zoom objektum hozzáadását a gyűjtemény végéhez (tételezzük fel, hogy a "Presentation.pptx" prezentációban legalább két szekció van): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISectionZoomFrame](../../isectionzoomframe/)
* Osztály [ISection](../../isection/)
* Osztály [IShapeCollection](../)
* Osztály [IPPImage](../../ippimage/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)