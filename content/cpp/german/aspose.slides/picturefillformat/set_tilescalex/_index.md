---
title: set_TileScaleX()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die horizontale Skalierung für die Texturfüllung als Prozentsatz fest. Schreiben Sie float.
type: docs
weight: 339
url: /de/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) Methode


Legt die horizontale Skalierung für die Texturfüllung als Prozentsatz fest. Schreiben Sie **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Bemerkungen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ruft das Bildfüllformat der Form ab
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