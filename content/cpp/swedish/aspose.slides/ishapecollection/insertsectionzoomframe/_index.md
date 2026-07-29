---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Section Zoom-ram och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 131
url: /sv/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) metod

Skapar en ny [Section](../../section/) Zoom-ram och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där [Section](../../section/) Zoom-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; måste tillhöra denna presentation och innehålla minst en bild. |

### Returvärde

Den nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Anmärkningar

Detta exempel demonstrerar skapandet och införandet av ett [Section](../../section/) Zoom-objekt på det angivna indexet i en samling (antag att det finns minst två sektioner i presentationen "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metod

Skapar en ny [Section](../../section/) Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där [Section](../../section/) Zoom-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; måste tillhöra denna presentation och innehålla minst en bild. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Bilden som ska visas i [Section](../../section/) Zoom-ramen. |

### Returvärde

Den nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Anmärkningar

Detta exempel demonstrerar skapandet och införandet av ett [Section](../../section/) Zoom-objekt på det angivna indexet i en samling (antag att det finns minst två sektioner i presentationen "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISectionZoomFrame](../../isectionzoomframe/)
* Klass [ISection](../../isection/)
* Klass [IShapeCollection](../)
* Klass [IPPImage](../../ippimage/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)