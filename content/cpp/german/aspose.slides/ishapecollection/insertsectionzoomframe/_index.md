---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Section-Zoom-Frame und fügt ihn in die Shape-Sammlung an dem angegebenen Index ein.
type: docs
weight: 131
url: /de/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) Methode

Erstellt einen neuen [Section](../../section/) Zoom-Frame und fügt ihn in die Shape-Sammlung an der angegebenen Position ein.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der [Section](../../section/) Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Der [ISection](../../isection/) auf den sich der [Section](../../section/) Zoom-Frame bezieht; er muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Bemerkungen

Dieses Beispiel zeigt die Erstellung und das Einfügen eines [Section](../../section/) Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen [Section](../../section/) Zoom-Frame mit einem vordefinierten Bild und fügt ihn in die Shape-Sammlung an der angegebenen Position ein.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der [Section](../../section/) Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Frames, in Punkten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Der [ISection](../../isection/) auf den sich der [Section](../../section/) Zoom-Frame bezieht; er muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das Bild, das im [Section](../../section/) Zoom-Frame angezeigt werden soll. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Bemerkungen

Dieses Beispiel zeigt die Erstellung und das Einfügen eines [Section](../../section/) Zoom-Objekts an dem angegebenen Index einer Sammlung (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält): 
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
* Klasse [IShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)