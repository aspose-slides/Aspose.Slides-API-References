---
title: get_ZoomImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt das Bild für das Zoom-Objekt. Lesen Sie IPPImage.
type: docs
weight: 79
url: /de/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() Methode

Ermittelt das Bild für das Zoom-Objekt. Lesen [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Hinweise

Das Beispiel zeigt das Ändern eines Bildes eines Zoom-Objekts:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)