---
title: get_ZoomImage()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει εικόνα για το αντικείμενο ζουμ. Διαβάστε IPPImage.
type: docs
weight: 79
url: /el/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() μέθοδος

Λαμβάνει την εικόνα για το αντικείμενο ζουμ. Διαβάστε [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Σχόλια

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
* Κλάση [IZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)