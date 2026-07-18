---
title: get_ImageType()
second_title: Aspose.Slides για την Αναφορά API C++
description: "Λαμβάνει τον τύπο εικόνας ενός αντικειμένου ζουμ. Διαβάστε ZoomImageType. Προεπιλεγμένη τιμή: Preview"
type: docs
weight: 1
url: /el/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() μέθοδος


Λαμβάνει τον τύπο εικόνας ενός αντικειμένου ζουμ. Διαβάστε [ZoomImageType](../../zoomimagetype/). Προεπιλεγμένη τιμή: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Παρατηρήσεις


Καθορίζει εάν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση διαφάνειας ή μια εικόνα εξώφυλλου. 

Το επόμενο παράδειγμα δείχνει την αλλαγή του Τύπου εικόνας στην τιμή Preview. Σε αυτήν την περίπτωση η τρέχουσα εικόνα ενός αντικειμένου Zoom αλλάζει σε εικόνα διαφάνειας: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Δείτε επίσης

* Απαρίθμηση [ZoomImageType](../../zoomimagetype/)
* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)