---
title: set_TileScaleY()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει την κάθετη κλίμακα για το γέμισμα υφής ως ποσοστό. Γράψτε float.
type: docs
weight: 365
url: /el/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) μέθοδος


Ορίζει την κάθετη κλίμακα για το γέμισμα υφής ως ποσοστό. Γράψτε **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
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
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)