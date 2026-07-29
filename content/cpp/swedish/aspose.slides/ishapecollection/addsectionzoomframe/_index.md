---
title: AddSectionZoomFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny Section Zoom-ram och lägger till den i slutet av formsamlingen.
type: docs
weight: 118
url: /sv/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) metod


Skapar en ny [Section](../../section/) Zoom-ram och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | den [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; måste tillhöra denna presentation och innehålla minst en bild. |

### Returvärde

Det nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Anmärkningar


Detta exempel demonstrerar hur man lägger till ett [Section](../../section/) Zoom-objekt i slutet av en samling (anta att det finns minst två sektioner i ”Presentation.pptx”-presentationen): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) metod


Skapar en ny [Section](../../section/) Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya [Section](../../section/) Zoom-ramen, i punkter. |
| width | **float** | bredden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| height | **float** | höjden på den nya [Section](../../section/) Zoom-ramen, i punkter. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | den [ISection](../../isection/) som refereras av [Section](../../section/) Zoom-ramen; måste tillhöra denna presentation och innehålla minst en bild. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | den [IPPImage](../../ippimage/) som ska visas i [Section](../../section/) Zoom-ramen. |

### Returvärde

Det nyss skapade [ISectionZoomFrame](../../isectionzoomframe/).

## Anmärkningar


Detta exempel demonstrerar hur man lägger till ett [Section](../../section/) Zoom-objekt i slutet av en samling (anta att det finns minst två sektioner i ”Presentation.pptx”-presentationen): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISectionZoomFrame](../../isectionzoomframe/)
* Klass [ISection](../../isection/)
* Klass [IShapeCollection](../)
* Klass [IPPImage](../../ippimage/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)