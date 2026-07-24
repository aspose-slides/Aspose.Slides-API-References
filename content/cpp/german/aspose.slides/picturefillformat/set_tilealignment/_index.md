---
title: set_TileAlignment()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt fest, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Startpunkt des Texturmusters und wie es sich über die Form wiederholt. Schreiben Sie RectangleAlignment.
type: docs
weight: 391
url: /de/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) Methode


Legt fest, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Startpunkt des Texturmusters und wie es sich über die Form wiederholt. Schreiben [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Hinweise


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

* Enum [RectangleAlignment](../../rectanglealignment/)
* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)