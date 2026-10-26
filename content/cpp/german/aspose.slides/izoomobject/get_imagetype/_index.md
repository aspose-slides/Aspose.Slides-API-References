---
title: get_ImageType()
second_title: Aspose.Slides für C++ API Referenz
description: "Ermittelt den Bildtyp eines Zoom-Objekts. Lesen Sie ZoomImageType. Standardwert: Preview"
type: docs
weight: 1
url: /de/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() Methode


Ermittelt den Bildtyp eines Zoom-Objekts. Lesen Sie [ZoomImageType](../../zoomimagetype/). Standardwert: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Hinweise


Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Deckblattbild verwendet. 

Dieses Beispiel demonstriert das Ändern von Image Type auf den Wert Preview. In diesem Fall ändert sich das aktuelle Bild eines Zoom-Objekts zu einem Folienbild: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Siehe auch

* Aufzählung [ZoomImageType](../../zoomimagetype/)
* Klasse [IZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)