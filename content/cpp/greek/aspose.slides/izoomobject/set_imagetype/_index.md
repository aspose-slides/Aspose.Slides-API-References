---
title: set_ImageType()
second_title: Aspose.Slides για την αναφορά API του C++
description: "Ορίζει τον τύπο εικόνας ενός αντικειμένου ζουμ. Γράψτε ZoomImageType. Προεπιλεγμένη τιμή: Preview"
type: docs
weight: 14
url: /el/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) μέθοδος


Ορίζει τον τύπο εικόνας ενός Zoom object. Γράψτε [ZoomImageType](../../zoomimagetype/). Προεπιλεγμένη τιμή: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Παρατηρήσεις


Καθορίζει εάν το Zoom object χρησιμοποιεί την προεπισκόπηση διαφάνειας ή μια εικόνα εξώφυλλου. 

Αυτό το παράδειγμα δείχνει την αλλαγή του Image Type στην τιμή Preview. Σε αυτήν την περίπτωση η τρέχουσα εικόνα ενός Zoom object αλλάζει σε εικόνα διαφάνειας: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Δείτε επίσης

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)