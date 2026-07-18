---
title: WriteAsEmf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF.
type: docs
weight: 170
url: /el/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) Μέθοδος


Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή στόχου |
## Παρατηρήσεις



Το παρακάτω παράδειγμα κώδικα δείχνει πώς να μετατρέψετε την πρώτη διαφάνεια από μια παρουσίαση PowerPoint σε μετααρχείο. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Αποθηκεύει την πρώτη διαφάνεια ως μετααρχείο
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Δείτε Επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [Slide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)