---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API referencia
description: Új Section Zoom keretet hoz létre, és a shape collection végéhez adja hozzá.
type: docs
weight: 131
url: /hu/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metódus

Új [Section](../../section/) Zoom keretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új [Section](../../section/) Zoom keret x-koordinátája, pontokban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y-koordinátája, pontokban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége, pontokban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága, pontokban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | A [Section](../../section/) Zoom keret által hivatkozott [ISection](../../isection/); a bemutatóhoz kell tartoznia, és legalább egy diát kell tartalmaznia. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések

Ez a példa bemutatja, hogyan lehet egy [Section](../../section/) Zoom objektumot hozzáadni a gyűjtemény végéhez (feltevés, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metódus

Új [Section](../../section/) Zoom keretet hoz létre előre definiált képpel, és a alakzatgyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új [Section](../../section/) Zoom keret x-koordinátája, pontokban. |
| y | **float** | Az új [Section](../../section/) Zoom keret y-koordinátája, pontokban. |
| width | **float** | Az új [Section](../../section/) Zoom keret szélessége, pontokban. |
| height | **float** | Az új [Section](../../section/) Zoom keret magassága, pontokban. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | A [Section](../../section/) Zoom keret által hivatkozott [ISection](../../isection/); a bemutatóhoz kell tartoznia, és legalább egy diát kell tartalmaznia. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A [IPPImage](../../ippimage/) a [Section](../../section/) Zoom kereten belül megjelenítendő. |

### Visszatérési érték

Az újonnan létrehozott [ISectionZoomFrame](../../isectionzoomframe/).

## Megjegyzések

Ez a példa bemutatja, hogyan lehet egy [Section](../../section/) Zoom objektumot hozzáadni a gyűjtemény végéhez (feltevés, hogy a "Presentation.pptx" bemutatóban legalább két szekció van):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)