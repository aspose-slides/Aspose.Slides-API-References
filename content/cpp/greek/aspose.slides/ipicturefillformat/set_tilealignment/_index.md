---
title: set_TileAlignment()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του προτύπου υφής και πώς επαναλαμβάνεται κατά μήκος του σχήματος. Γράψτε RectangleAlignment.
type: docs
weight: 391
url: /el/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) μέθοδος

Ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του προτύπου υφής και πώς επαναλαμβάνεται κατά μήκος του σχήματος. Γράψτε [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Παρατηρήσεις

Η προεπιλογή είναι [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την ευθυγράμμιση της επικάλυψης στην κάτω δεξιά γωνία
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Δείτε επίσης

* Enum [RectangleAlignment](../../rectanglealignment/)
* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)