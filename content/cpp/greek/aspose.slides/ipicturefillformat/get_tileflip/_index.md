---
title: get_TileFlip()
second_title: Αναφορά API Aspose.Slides για C++
description: "Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κάθετο ή και τους δύο άξονες. Διαβάστε Slides::TileFlip."
type: docs
weight: 404
url: /el/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() μέθοδος


Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κάθετο ή και τους δύο άξονες. Διαβάστε [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
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

// Αναστρέφει το πλακίδιο υφής γύρω από τον κάθετο άξονα.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Δείτε επίσης

* Απαρίθμηση [TileFlip](../../tileflip/)
* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)