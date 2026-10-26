---
title: set_ZoomImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt das Bild für das Zoom-Objekt. Schreiben IPPImage.
type: docs
weight: 92
url: /de/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) Methode


Setzt das Bild für das Zoom-Objekt. Schreiben [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Hinweise


Das Beispiel demonstriert das Ändern eines Bildes eines Zoom-Objekts: 
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