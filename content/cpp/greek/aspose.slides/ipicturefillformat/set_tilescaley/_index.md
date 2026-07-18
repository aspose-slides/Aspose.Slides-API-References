---
title: set_TileScaleY()
second_title: Aspose.Slides για την αναφορά API του C++
description: Ορίζει την κάθετη κλίμακα για τη συμπλήρωση υφής ως ποσοστό. Γράψτε float.
type: docs
weight: 365
url: /el/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) μέθοδος

Ορίζει την κάθετη κλίμακα για τη συμπλήρωση υφής ως ποσοστό. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
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

* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)