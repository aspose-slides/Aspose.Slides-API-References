---
title: set_ImageType()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt den Bildtyp eines Zoom-Objekts fest. Schreiben Sie ZoomImageType. Standardwert: Preview"
type: docs
weight: 14
url: /de/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) Methode


Legt den Bildtyp eines Zoom-Objekts fest. Schreiben Sie [ZoomImageType](../../zoomimagetype/). Standardwert: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Hinweise


Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Deckblattbild verwendet. 

Das nächste Beispiel zeigt, wie der Bildtyp auf den Wert Preview geändert wird. In diesem Fall ändert sich das aktuelle Bild eines Zoom-Objekts in das Folienbild: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Siehe auch

* Enum [ZoomImageType](../../zoomimagetype/)
* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)