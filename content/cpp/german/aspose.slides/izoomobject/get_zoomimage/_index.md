---
title: get_ZoomImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft das Bild für das Zoom-Objekt ab. Siehe IPPImage.
type: docs
weight: 79
url: /de/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() Methode

Ruft das Bild für das Zoom-Objekt ab. Siehe [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Bemerkungen

Das Beispiel demonstriert, wie das Bild eines Zoom-Objekts geändert wird:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)