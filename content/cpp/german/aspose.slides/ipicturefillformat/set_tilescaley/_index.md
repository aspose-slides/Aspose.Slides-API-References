---
title: set_TileScaleY()
second_title: Aspose.Slides für C++ API Referenz
description: Setzt den vertikalen Maßstab für die Texturfüllung als Prozentsatz. Schreiben Sie float.
type: docs
weight: 365
url: /de/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) Methode


Geben Sie **float** an.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Kachel
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt die vertikale Skalierung für die Textur auf 120 Prozent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Siehe auch

* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)