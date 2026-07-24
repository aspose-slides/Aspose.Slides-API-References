---
title: get_TileScaleX()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück. Lese float.
type: docs
weight: 326
url: /de/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() Methode


Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück. Lesen **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Holt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt die horizontale Skalierung für die Textur auf 120 Prozent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Siehe auch

* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)