---
title: get_TileAlignment()
second_title: Aspose.Slides για το API C++
description: Επιστρέφει πώς ευθυγραμμίζεται η υφή εντός του σχήματος. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου υφής και πώς επαναλαμβάνεται σε όλο το σχήμα. Διαβάστε RectangleAlignment.
type: docs
weight: 378
url: /el/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() μέθοδος

Επιστρέφει πώς ευθυγραμμίζεται η υφή εντός του σχήματος. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου υφής και πώς επαναλαμβάνεται σε όλο το σχήμα. Διαβάστε [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
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

// Ορίζει τη στοίχιση για το πλακίδιο στο δεξί κάτω
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Δείτε επίσης

* Enum [RectangleAlignment](../../rectanglealignment/)
* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)