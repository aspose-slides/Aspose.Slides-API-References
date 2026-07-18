---
title: get_TileAlignment()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει πώς ευθυγραμμίζεται η υφή εντός του σχήματος. Αυτή η ρύθμιση ελέγχει το αρχικό σημείο του προτύπου υφής και πώς επαναλαμβάνεται σε όλο το σχήμα. Διαβάστε RectangleAlignment.
type: docs
weight: 378
url: /el/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() μέθοδος

Επιστρέφει πώς ευθυγραμμίζεται η υφή εντός του σχήματος. Αυτή η ρύθμιση ελέγχει το αρχικό σημείο του προτύπου υφής και πώς επαναλαμβάνεται σε όλο το σχήμα. Διαβάστε [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
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

// Ορίζει την ευθυγράμμιση της πλακόστρωσης στο δεξί κάτω
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Δείτε επίσης

* Enum [RectangleAlignment](../../rectanglealignment/)
* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)