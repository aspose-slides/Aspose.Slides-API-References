---
title: get_ZoomImage()
second_title: Aspose.Slides για την Αναφορά API C++
description: Λαμβάνει εικόνα για το αντικείμενο Zoom. Διαβάστε IPPImage.
type: docs
weight: 79
url: /el/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() method

Λαμβάνει την εικόνα για το αντικείμενο Zoom. Διαβάστε [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Παρατηρήσεις

Το παράδειγμα δείχνει την αλλαγή μιας εικόνας ενός αντικειμένου Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)