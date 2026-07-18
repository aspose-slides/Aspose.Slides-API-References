---
title: get_TileScaleY()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την κάθετη κλίμακα για τη γεμιστική υφή ως ποσοστό. Ανάγνωση float.
type: docs
weight: 352
url: /el/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() μέθοδος

Επιστρέφει την κατακόρυφη κλίμακα για τη γεμιστική υφή ως ποσοστό. Ανάγνωση **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την κάθετη κλίμακα για την υφή σε 120 τοις εκατό
pictureFillFormat->set_TileScaleY(120.0f);
```

## Δείτε επίσης

* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)