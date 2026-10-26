---
title: set_ZoomImage()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει την εικόνα για το αντικείμενο ζουμ. Γράψτε IPPImage.
type: docs
weight: 92
url: /el/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) μέθοδος

Ορίζει την εικόνα για το αντικείμενο ζουμ. Γράψτε [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
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
* Κλάση [IZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)