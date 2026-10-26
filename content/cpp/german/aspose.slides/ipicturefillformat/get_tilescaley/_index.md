---
title: get_TileScaleY()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück. Lese float.
type: docs
weight: 352
url: /de/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() Methode


Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück. Lese **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Bemerkungen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt den vertikalen Maßstab für die Textur auf 120 Prozent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Siehe auch

* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)