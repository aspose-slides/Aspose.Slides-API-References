---
title: get_TileScaleY()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει την κάθετη κλίμακα για τη συμπλήρωση υφής ως ποσοστό. Διαβάζει float.
type: docs
weight: 352
url: /el/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() μέθοδος

Επιστρέφει την κάθετη κλίμακα για τη συμπλήρωση υφής ως ποσοστό. Διαβάζει **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την κάθετη κλίμακα για την υφή στο 120 τοις εκατό
pictureFillFormat->set_TileScaleY(120.0f);
```

## Δείτε επίσης

* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)