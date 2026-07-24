---
title: set_TileScaleX()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die horizontale Skalierung für die Texturfüllung als Prozentsatz fest. Schreiben Sie float.
type: docs
weight: 339
url: /de/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) Methode

Sets the horizontal scale for the texture fill as a percentage. Write **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt die horizontale Skalierung für die Textur auf 120 Prozent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Siehe auch

* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)