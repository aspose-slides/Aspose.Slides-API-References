---
title: CompressImage()
second_title: Aspose.Slides για το API αναφοράς C++
description: Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.
type: docs
weight: 443
url: /el/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) μέθοδος

Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Εάν είναι true, η μέθοδος θα αφαιρέσει τις περικομμένες περιοχές της εικόνας, μειώνοντας ενδεχομένως περαιτέρω το μέγεθός της. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Η στοχευόμενη ανάλυση για τη συμπίεση, καθορισμένη ως τιμή του enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Τιμή επιστροφής

Ένα **bool** που υποδεικνύει αν η εικόνα συμπιέστηκε επιτυχώς. Επιστρέφει ****true****

## Σχόλια

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη λειτουργία "Picture Format -> Compress Pictures" του PowerPoint.

αν η εικόνα έχει αλλαγεί το μέγεθος ή έχει περικοπεί, διαφορετικά ****false****

. 

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη **CompressImage** μέθοδο για να μειώσετε το μέγεθος μιας εικόνας σε μια παρουσίαση ορίζοντας μια στόχο ανάλυση και αφαιρώντας τις περικομμένες περιοχές: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Συμπιέστε την εικόνα με στόχο την ανάλυση 150 DPI (ανάλυση ιστού) και αφαιρέστε τις περικομμένες περιοχές
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) μέθοδος

Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Εάν είναι true, η μέθοδος θα αφαιρέσει τις περικομμένες περιοχές της εικόνας, μειώνοντας ενδεχομένως περαιτέρω το μέγεθός της. |
| resolution | **float** | Η στοχευόμενη ανάλυση σε DPI. Η τιμή πρέπει να είναι θετική και καθορίζει πώς θα αλλάξει το μέγεθος της εικόνας. |

### Τιμή επιστροφής

Ένα **bool** που υποδεικνύει αν η εικόνα συμπιέστηκε επιτυχώς. Επιστρέφει ****true****

## Σχόλια

Αυτή η μέθοδος αλλάζει το μέγεθος και την ανάλυση της εικόνας παρόμοια με τη λειτουργία "Picture Format -> Compress Pictures" του PowerPoint.

αν η εικόνα έχει αλλαγεί το μέγεθος ή έχει περικοπεί, διαφορετικά ****false****

. 

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη **CompressImage** μέθοδο για να μειώσετε το μέγεθος μιας εικόνας σε μια παρουσίαση ορίζοντας μια στόχο ανάλυση και αφαιρώντας τις περικομμένες περιοχές: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει το PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Συμπιέστε την εικόνα με στόχο ανάλυση 150 DPI (ανάλυση ιστού) και αφαιρέστε τις περικομμένες περιοχές
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Ανάλυση ιστού
```

## Δείτε επίσης

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)