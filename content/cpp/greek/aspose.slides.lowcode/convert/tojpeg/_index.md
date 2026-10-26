---
title: ToJpeg()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει την παρουσίαση εισόδου σε σύνολο εικόνων μορφής JPEG.  Εάν το όνομα αρχείου εξόδου δίνεται ως \"myPath/myFilename.jpeg\", το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων \"myPath/myFilename_N.jpeg\", όπου N είναι ο αριθμός της διαφάνειας.
type: docs
weight: 40
url: /el/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) μέθοδος

Μετατρέπει την παρουσίαση εισόδου σε σύνολο εικόνων μορφής JPEG. 

Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η παρουσίαση εισόδου. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα αρχείου εξόδου. |
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) μέθοδος

Μετατρέπει την παρουσίαση εισόδου σε σύνολο εικόνων μορφής JPEG. 

Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η παρουσίαση εισόδου |
| outputFileName | [System::String](../../../system/string/) | Το όνομα αρχείου εξόδου. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Το μέγεθος της κάθε παραγόμενης εικόνας. |
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) μέθοδος

Μετατρέπει την παρουσίαση εισόδου σε σύνολο εικόνων μορφής JPEG. 

Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η παρουσίαση εισόδου. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα αρχείου εξόδου. |
| scale | **float** | Ο συντελεστής κλιμάκωσης που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Οι επιλογές απόδοσης. |
## Παρατηρήσεις

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [String](../../../system/string/)
* Κλάση [Convert](../)
* Κλάση [Size](../../../system.drawing/size/)
* Κλάση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)