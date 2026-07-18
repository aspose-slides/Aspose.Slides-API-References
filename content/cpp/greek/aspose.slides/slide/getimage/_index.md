---
title: GetImage()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.
type: docs
weight: 144
url: /el/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | **float** | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή Επιστροφής

[IImage](../../iimage/) αντικείμενο.

## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε μικρογραφίες από το PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε διαφάνειες σε bitmap και να αποθηκεύσετε τις εικόνες σε PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Μετατρέπει την πρώτη διαφάνεια της παρουσίασης σε αντικείμενο Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Αποθηκεύει την εικόνα σε μορφή PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε PowerPoint PPT/PPTX σε JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Δημιουργεί εικόνα πλήρους κλίμακας
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Αποθηκεύει την εικόνα στο δίσκο σε μορφή JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε PowerPoint PPT/PPTX σε JPG με προσαρμοσμένες διαστάσεις: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Ορισμός διαστάσεων
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Λήψη κλιμακωμένων τιμών του X και Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Δημιουργία εικόνας πλήρους κλίμακας
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή Επιστροφής

Image αντικείμενο.

## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε διαφάνειες σε εικόνες με προσαρμοσμένα μεγέθη χρησιμοποιώντας C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Μετατρέπει την πρώτη διαφάνεια στην παρουσίαση σε Bitmap με το καθορισμένο μέγεθος
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Αποθηκεύει την εικόνα σε μορφή JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail tiff image με συγκεκριμένες παραμέτρους.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Επιλογές Tiff. |

### Τιμή Επιστροφής

Image αντικείμενο.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές απόδοσης. |

### Τιμή Επιστροφής

Image αντικείμενο.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές απόδοσης. |
| scaleX | **float** | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή κατά την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή Επιστροφής

Αντικείμενα Bitmap.

## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε διαφάνειες με σημειώσεις και σχόλια σε [Images](../../images/) χρησιμοποιώντας C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Δημιουργεί τις επιλογές απόδοσης
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Δημιουργεί επιλογές διάταξης σημειώσεων και σχολίων
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Ορίζει τη θέση των σημειώσεων στη σελίδα
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Ορίζει τη θέση των σχολίων στη σελίδα
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Ορίζει το πλάτος της περιοχής εξόδου των σχολίων
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Ορίζει το χρώμα για την περιοχή σχολίων
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Ορίζει τις επιλογές διάταξης για την απόδοση
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Μετατρέπει την πρώτη διαφάνεια της παρουσίασης σε αντικείμενο IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Αποθηκεύει την εικόνα σε μορφή GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές απόδοσης. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή Επιστροφής

Image αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [Slide](../)
* Κλάση [Size](../../../system.drawing/size/)
* Κλάση [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Κλάση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)