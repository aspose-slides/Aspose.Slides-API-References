---
title: get_TileAlignment()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Ausgangspunkt des Texturmusters und wie es sich über die Form wiederholt. Lesen Sie RectangleAlignment.
type: docs
weight: 378
url: /de/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() Methode


Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Ausgangspunkt des Texturmusters und wie es sich über die Form wiederholt. Lesen Sie [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
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

// Setzt die Ausrichtung für die Kachelung nach rechts unten
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Siehe auch

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)