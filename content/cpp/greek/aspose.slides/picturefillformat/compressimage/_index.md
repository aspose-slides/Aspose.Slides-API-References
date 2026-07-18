---
title: CompressImage()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.
type: docs
weight: 443
url: /el/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) μέθοδος

Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Εάν είναι true, η μέθοδος θα αφαιρέσει τις περικομμένες περιοχές της εικόνας, ενδεχομένως μειώνοντας περαιτέρω το μέγεθός της. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Η στοχευμένη ανάλυση για τη συμπίεση, καθορισμένη ως τιμή του enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Τιμή Επιστροφής

Ένα **bool** που υποδεικνύει αν η εικόνα συμπιέστηκε επιτυχώς. Επιστρέφει ****true****

## Παρατηρήσεις

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη δυνατότητα "Picture Format -> Compress Pictures" του PowerPoint.

εάν η εικόνα επαναμετρήθηκε ή περικόπηκε, διαφορετικά ****false****

. 

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη μέθοδο **CompressImage** για να μειώσετε το μέγεθος μιας εικόνας σε μια παρουσίαση ορίζοντας μια στοχευμένη ανάλυση και αφαιρώντας τις περικομμένες περιοχές:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Συμπιέζει την εικόνα με στοχευμένη ανάλυση 150 DPI (ανάλυση ιστού) και αφαιρεί τις περικομμένες περιοχές
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) μέθοδος

Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Εάν είναι true, η μέθοδος θα αφαιρέσει τις περικομμένες περιοχές της εικόνας, ενδεχομένως μειώνοντας περαιτέρω το μέγεθός της. |
| resolution | **float** | Η στοχευμένη ανάλυση σε DPI. Αυτή η τιμή πρέπει να είναι θετική και ορίζει πώς θα αλλάξει το μέγεθος της εικόνας. |

### Τιμή Επιστροφής

Ένα **bool** που υποδεικνύει αν η εικόνα συμπιέστηκε επιτυχώς. Επιστρέφει ****true****

## Παρατηρήσεις

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη δυνατότητα "Picture Format -> Compress Pictures" του PowerPoint.

εάν η εικόνα επαναμετρήθηκε ή περικόπηκε, διαφορετικά ****false****

. 

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη μέθοδο **CompressImage** για να μειώσετε το μέγεθος μιας εικόνας σε μια παρουσίαση ορίζοντας μια στοχευμένη ανάλυση και αφαιρώντας τις περικομμένες περιοχές:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει το PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Συμπιέζει την εικόνα με στοχευμένη ανάλυση 150 DPI (ανάλυση Web) και αφαιρεί τις περικομμένες περιοχές
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // ανάλυση Web
```

## See Also

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)