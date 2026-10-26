---
title: AddSectionZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Section-Zoom-Rahmen und fügt ihn am Ende der ShapeCollection hinzu.
type: docs
weight: 131
url: /de/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) Methode

Erstellt einen neuen [Section](../../section/) Zoom-Rahmen und fügt ihn am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Das [ISection](../../isection/) auf das vom [Section](../../section/) Zoom-Frame verwiesen wird; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Anmerkungen

Dieses Beispiel zeigt, wie ein [Section](../../section/) Zoom-Objekt am Ende einer Sammlung hinzugefügt wird (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen [Section](../../section/) Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Das [ISection](../../isection/) auf das vom [Section](../../section/) Zoom-Frame verwiesen wird; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das [IPPImage](../../ippimage/) zur Anzeige innerhalb des [Section](../../section/) Zoom-Rahmens. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Anmerkungen

Dieses Beispiel zeigt, wie ein [Section](../../section/) Zoom-Objekt am Ende einer Sammlung hinzugefügt wird (es wird angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISectionZoomFrame](../../isectionzoomframe/)
* Klasse [ISection](../../isection/)
* Klasse [ShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)