---
title: DeletePictureCroppedAreas()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαγραφή των περικομμένων περιοχών του γεμίσματος Picture.
type: docs
weight: 430
url: /el/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() μέθοδος

Διαγράψτε τις περικομμένες περιοχές του γεμίσματος [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Τιμή Επιστροφής

Περικομμένη εικόνα ή αρχική εικόνα εάν η περικοπή δεν είναι απαραίτητη.

## Σχόλια

Αυτή η μέθοδος μετατρέπει τα μετααρχεία WMF/EMF σε raster PNG εικόνα κατά την περικοπή.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει το PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Διαγράφει τις περικομμένες περιοχές της εικόνας PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)