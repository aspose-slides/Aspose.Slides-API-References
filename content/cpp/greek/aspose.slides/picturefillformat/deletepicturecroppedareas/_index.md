---
title: DeletePictureCroppedAreas()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαγραφή περικομμένων περιοχών της γεμίσματος Picture.
type: docs
weight: 430
url: /el/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() μέθοδος


Διαγραφή περικομμένων περιοχών της γεμίσματος [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### Τιμή Επιστροφής

Περικομμένη εικόνα ή αρχική εικόνα εάν η περικοπή δεν είναι απαραίτητη.
## Σχόλια


Αυτή η μέθοδος μετατρέπει τα μετααρχεία WMF/EMF σε raster PNG εικόνα ενώ κάνει περικοπή.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Αποκτά το PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Διαγράφει τις περικομμένες περιοχές της εικόνας PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)