---
title: set_TileScaleX()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει την οριζόντια κλίμακα για τη γέμιση υφής ως ποσοστό. Γράψτε float.
type: docs
weight: 339
url: /el/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) μέθοδος

Ορίζει την οριζόντια κλίμακα για τη γέμιση υφής ως ποσοστό. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γέμισης εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γέμισης εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την οριζόντια κλίμακα για την υφή στο 120 τοις εκατό
pictureFillFormat->set_TileScaleX(120.0f);
```

## Δείτε επίσης

* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)