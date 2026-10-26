---
title: ToTiff()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής TIFF. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff", το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας.
type: docs
weight: 66
url: /el/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) μέθοδος

Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής TIFF.  

Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff", το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η εισαγόμενη παρουσίαση. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα αρχείου εξόδου. |

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) μέθοδος

Μετατρέπει την εισαγόμενη παρουσίαση σε μορφή TIFF με προσαρμοσμένες επιλογές. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff" και *multipage* είναι **false**, το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας. Διαφορετικά, εάν *multipage* είναι **true**, το αποτέλεσμα θα είναι ένα πολυσέλιδο έγγραφο "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η εισαγόμενη παρουσίαση. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα αρχείου εξόδου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Οι επιλογές αποθήκευσης TIFF. |
| multipage | **bool** | Καθορίζει αν το δημιουργημένο έγγραφο TIFF πρέπει να είναι πολυσέλιδο. |

## Παρατηρήσεις

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [String](../../../system/string/)
* Κλάση [Convert](../)
* Κλάση [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)