---
title: set_TileScaleX()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει την οριζόντια κλίμακα του γεμίσματος υφής ως ποσοστό. Γράψτε float.
type: docs
weight: 339
url: /el/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) μέθοδος


Ορίζει την οριζόντια κλίμακα του γεμίσματος υφής ως ποσοστό. Γράψτε **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Αποκτά τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την οριζόντια κλίμακα της υφής σε 120 τοις εκατό
pictureFillFormat->set_TileScaleX(120.0f);
```

## Δείτε επίσης

* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)