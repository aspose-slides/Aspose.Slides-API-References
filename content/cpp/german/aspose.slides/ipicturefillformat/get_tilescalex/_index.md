---
title: get_TileScaleX()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt den horizontalen Maßstab für die Texturfüllung als Prozentsatz zurück. Lese float.
type: docs
weight: 326
url: /de/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() Methode

Gibt den horizontalen Maßstab für die Texturfüllung als Prozentsatz zurück. Lesen **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```
## Hinweise


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Kachel
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt den horizontalen Maßstab für die Textur auf 120 Prozent
pictureFillFormat->set_TileScaleX(120.0f);
```
## Siehe auch

* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)