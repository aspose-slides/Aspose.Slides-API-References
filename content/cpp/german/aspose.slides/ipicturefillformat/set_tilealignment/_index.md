---
title: set_TileAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt fest, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Ausgangspunkt des Texturmusters und wie es über die Form wiederholt wird. Schreiben Sie RectangleAlignment.
type: docs
weight: 391
url: /de/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) Methode

Legt fest, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Ausgangspunkt des Texturmusters und wie es über die Form wiederholt wird. Schreiben Sie [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Bemerkungen

Standard ist [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ruft das Bildfüllformat der Form ab
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt die Ausrichtung für die Kachelung auf rechts unten
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Siehe auch

* Aufzählung [RectangleAlignment](../../rectanglealignment/)
* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)