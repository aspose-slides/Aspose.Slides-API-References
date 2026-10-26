---
title: ToPng()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG.  Αν το όνομα του αρχείου εξόδου δοθεί ως \"myPath/myFilename.png\", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων \"myPath/myFilename_N.png\", όπου N είναι ο αριθμός της διαφάνειας.
type: docs
weight: 53
url: /el/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) μέθοδος


Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG. 

 Αν το όνομα του αρχείου εξόδου δοθεί ως \"myPath/myFilename.png\", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων \"myPath/myFilename_N.png\", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η εισαγόμενη παρουσίαση. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα του αρχείου εξόδου. |
## Σημειώσεις




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) μέθοδος


Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG. 

 Αν το όνομα του αρχείου εξόδου δοθεί ως \"myPath/myFilename.png\", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων \"myPath/myFilename_N.png\", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η εισαγόμενη παρουσίαση |
| outputFileName | [System::String](../../../system/string/) | Το όνομα του αρχείου εξόδου. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Το μέγεθος κάθε παραγόμενης εικόνας. |
## Σημειώσεις 




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) μέθοδος


Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG. 

 Αν το όνομα του αρχείου εξόδου δοθεί ως \"myPath/myFilename.png\", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων \"myPath/myFilename_N.png\", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η εισαγόμενη παρουσίαση. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα του αρχείου εξόδου. |
| scale | **float** | Ο συντελεστής κλίμακας που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Οι επιλογές απόδοσης. |
## Σημειώσεις 




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [String](../../../system/string/)
* Κλάση [Convert](../)
* Κλάση [Size](../../../system.drawing/size/)
* Κλάση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)