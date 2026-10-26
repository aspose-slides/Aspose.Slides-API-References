---
title: get_TileFlip()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Γυρίζει το πλακίδιο υφής γύρω από την οριζόντια, την κάθετη ή και τις δύο άξονες. Διαβάστε Slides::TileFlip."
type: docs
weight: 404
url: /el/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() μέθοδος


Γυρίζει το πλακίδιο υφής γύρω από την οριζόντια, την κάθετη ή και τις δύο άξονες. Διαβάστε [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Παρατηρήσεις


Η προεπιλογή είναι [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Αναστρέφει το πλακίδιο υφής γύρω από τον κατακόρυφο άξονα.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Δείτε επίσης

* Απαρίθμηση [TileFlip](../../tileflip/)
* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)