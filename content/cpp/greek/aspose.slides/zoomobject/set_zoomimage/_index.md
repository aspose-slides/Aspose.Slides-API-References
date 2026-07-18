---
title: set_ZoomImage()
second_title: Aspose.Slides για την αναφορά API C++
description: Ορίζει εικόνα για το αντικείμενο ζουμ. Γράψτε IPPImage.
type: docs
weight: 92
url: /el/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) μέθοδος

Ορίζει εικόνα για το αντικείμενο ζουμ. Γράψτε [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
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

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)