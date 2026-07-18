---
title: WriteAsEmf()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αποθηκεύει την εικόνα SVG ως αρχείο EMF.
type: docs
weight: 53
url: /el/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) μέθοδος


Αποθηκεύει την εικόνα SVG ως αρχείο EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Στοχευόμενη ροή |
## Παρατηρήσεις



Το παρακάτω παράδειγμα δείχνει πώς να αποθηκεύσετε την εικόνα SVG σε μετααρχείο. 
```cpp
// Δημιουργεί τη νέα εικόνα SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Αποθηκεύει την εικόνα SVG ως μετααρχείο
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Αυτό το δείγμα δείχνει πώς να προσθέσετε την εικόνα SVG ως μετααρχείο στη συλλογή εικόνων της παρουσίασης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Δημιουργεί τη νέα εικόνα SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Αποθηκεύει την εικόνα SVG ως μετααρχείο
svgImage->WriteAsEmf(memStream);
// Προσθέτει το μετααρχείο στη συλλογή εικόνων
pres->get_Images()->AddImage(memStream->ToArray());
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [ISvgImage](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)