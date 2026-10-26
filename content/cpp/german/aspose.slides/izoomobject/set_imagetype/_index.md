---
title: set_ImageType()
second_title: Aspose.Slides für C++ API-Referenz
description: "Setzt den Bildtyp eines Zoom-Objekts. Schreiben Sie ZoomImageType. Standardwert: Preview"
type: docs
weight: 14
url: /de/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) method


Setzt den Bildtyp eines Zoom-Objekts. Schreiben Sie [ZoomImageType](../../zoomimagetype/). Standardwert: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Hinweise


Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Titelbild verwendet. 

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