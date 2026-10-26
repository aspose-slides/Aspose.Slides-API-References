---
title: AddSectionZoomFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Section-Zoom-Rahmen und fügt ihn am Ende der Shape-Sammlung hinzu.
type: docs
weight: 118
url: /de/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) Methode


Erstellt ein neues [Section](../../section/) Zoom-Rahmen und fügt es am Ende der Shape-Sammlung hinzu.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Der [ISection](../../isection/) auf den der [Section](../../section/) Zoom-Rahmen verweist; er muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Hinweise


Dieses Beispiel demonstriert das Hinzufügen eines [Section](../../section/) Zoom-Objekts zum Ende einer Sammlung (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) Methode


Erstellt ein neues [Section](../../section/) Zoom-Rahmen mit einem vordefinierten Bild und fügt es am Ende der Shape-Sammlung hinzu.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen [Section](../../section/) Zoom-Rahmens, in Punkten. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Der [ISection](../../isection/) auf den der [Section](../../section/) Zoom-Rahmen verweist; er muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das [IPPImage](../../ippimage/) zur Anzeige im [Section](../../section/) Zoom-Rahmen. |

### Rückgabewert

Der neu erstellte [ISectionZoomFrame](../../isectionzoomframe/).

## Hinweise


Dieses Beispiel demonstriert das Hinzufügen eines [Section](../../section/) Zoom-Objekts zum Ende einer Sammlung (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [ISectionZoomFrame](../../isectionzoomframe/)
* Klasse [ISection](../../isection/)
* Klasse [IShapeCollection](../)
* Klasse [IPPImage](../../ippimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)