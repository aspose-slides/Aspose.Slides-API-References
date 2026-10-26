---
title: set_TileAlignment()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο εκκίνησης του μοτίβου της υφής και το πώς επαναλαμβάνεται στο σχήμα. Γράψτε RectangleAlignment.
type: docs
weight: 391
url: /el/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) μέθοδος

Ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. Αυτή η ρύθμιση ελέγχει το σημείο έναρξης του μοτίβου της υφής και πώς επαναλαμβάνεται στο σχήμα. Γράψτε [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Σχόλια

Η προεπιλογή είναι [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την ευθυγράμμιση της επικάλυψης στην κάτω δεξιά
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Δείτε επίσης

* Απαρίθμηση [RectangleAlignment](../../rectanglealignment/)
* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)