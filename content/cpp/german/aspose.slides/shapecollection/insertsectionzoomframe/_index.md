---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Section Zoom-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein.
type: docs
weight: 144
url: /de/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) Methode


Erstellt einen neuen [Section](../../section/) Zoom-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der [Section](../../section/) Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Der [ISection](../../isection/), auf den sich der [Section](../../section/) Zoom-Frame bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Bemerkungen


Dieses Beispiel demonstriert das Erstellen und Einfügen eines [Section](../../section/) Zoom-Objekts an der angegebenen Position einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) Methode


Erstellt einen neuen [Section](../../section/) Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Shape-Collection ein.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der [Section](../../section/) Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Frames, in Punkt. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Der [ISection](../../isection/), auf den sich der [Section](../../section/) Zoom-Frame bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das Bild, das im [Section](../../section/) Zoom-Frame angezeigt werden soll. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Bemerkungen


Dieses Beispiel demonstriert das Erstellen und Einfügen eines [Section](../../section/) Zoom-Objekts an der angegebenen Position einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISectionZoomFrame](../../isectionzoomframe/)
* Klasse [ISection](../../isection/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)