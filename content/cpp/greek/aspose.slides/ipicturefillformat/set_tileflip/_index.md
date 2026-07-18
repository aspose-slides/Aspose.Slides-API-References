---
title: set_TileFlip()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κατακόρυφο ή και τους δύο άξονες. Γράψτε Slides::TileFlip."
type: docs
weight: 417
url: /el/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) μέθοδος


Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κατακόρυφο ή και τους δύο άξονες. Γράψτε [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Παρατηρήσεις


Η προεπιλογή είναι [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Αποκτά τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Αναστρέφει το πλακίδιο υφής γύρω από τον κατακόρυφο άξονα.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Δείτε επίσης

* Enum [TileFlip](../../tileflip/)
* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)