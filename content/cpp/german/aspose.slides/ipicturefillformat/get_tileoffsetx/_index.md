---
title: get_TileOffsetX()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert verschiebt sie nach links. Lese float.
type: docs
weight: 274
url: /de/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() Methode

Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert verschiebt sie nach links. Lese **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Anmerkungen

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ruft das Bildfüllformat der Form ab
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Kachel
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt den horizontalen Versatz der Textur auf 20 Punkte
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Siehe auch

* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)