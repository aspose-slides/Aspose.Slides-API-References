---
title: set_ImageType()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ορίζει τον τύπο εικόνας ενός αντικειμένου ζουμ. Γράψτε ZoomImageType. Προεπιλεγμένη τιμή: Preview"
type: docs
weight: 14
url: /el/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) μέθοδος


Ορίζει τον τύπο εικόνας ενός αντικειμένου ζουμ. Γράψτε [ZoomImageType](../../zoomimagetype/). Προεπιλεγμένη τιμή: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Παρατηρήσεις


Καθορίζει εάν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση της διαφάνειας ή μια εικόνα εξώφυλλου. 

Το παρακάτω παράδειγμα δείχνει την αλλαγή του τύπου εικόνας στην τιμή Preview. Σε αυτή την περίπτωση η τρέχουσα εικόνα ενός αντικειμένου Zoom αλλάζει σε εικόνα διαφάνειας: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Δείτε επίσης

* Απαριθμητικό [ZoomImageType](../../zoomimagetype/)
* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)