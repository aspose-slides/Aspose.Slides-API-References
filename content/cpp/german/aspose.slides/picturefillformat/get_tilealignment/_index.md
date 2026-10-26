---
title: get_TileAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Startpunkt des Texturmusters und wie es über die Form hinweg wiederholt wird. Lesen Sie RectangleAlignment.
type: docs
weight: 378
url: /de/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() Methode

Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Startpunkt des Texturmusterns und wie es über die Form hinweg wiederholt wird. Lesen Sie [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Hinweise

Standard ist [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Kachel
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt die Ausrichtung der Kachelung auf rechts unten
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Siehe auch

* Aufzählung [RectangleAlignment](../../rectanglealignment/)
* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)