---
title: set_TileScaleY()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die vertikale Skalierung der Texturfüllung als Prozentsatz fest. Schreiben float.
type: docs
weight: 365
url: /de/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) method

Setzt die vertikale Skalierung für die Texturfüllung als Prozentsatz. Schreiben **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Bemerkungen

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ruft das Bildfüllformat der Form ab
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt die vertikale Skalierung der Textur auf 120 Prozent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Siehe auch

* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)