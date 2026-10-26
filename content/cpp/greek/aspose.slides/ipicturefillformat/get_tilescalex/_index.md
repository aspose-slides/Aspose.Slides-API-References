---
title: get_TileScaleX()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την οριζόντια κλίμακα για τη γέμιση υφής ως ποσοστό. Ανάγνωση float.
type: docs
weight: 326
url: /el/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() μέθοδος


Επιστρέφει την οριζόντια κλίμακα για τη γέμιση υφής ως ποσοστό. Ανάγνωση **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει τη οριζόντια κλίμακα για την υφή στο 120 τοις εκατό
pictureFillFormat->set_TileScaleX(120.0f);
```

## Δείτε επίσης

* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)