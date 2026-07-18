---
title: WriteAsEmf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποθηκεύει την εικόνα SVG ως αρχείο EMF.
type: docs
weight: 66
url: /el/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Αποθηκεύει την εικόνα SVG ως αρχείο EMF.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή στόχου |
## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να αποθηκεύσετε την εικόνα SVG σε ένα μετααρχείο. 
```cpp
// Δημιουργεί τη νέα εικόνα SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Αποθηκεύει την εικόνα SVG ως μετααρχείο
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Αυτό το παράδειγμα δείχνει πώς να προσθέσετε την εικόνα SVG ως μετααρχείο στη συλλογή εικόνων της παρουσίασης. 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [SvgImage](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)