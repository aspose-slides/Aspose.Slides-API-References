---
title: get_TileOffsetX()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Lies float.
type: docs
weight: 274
url: /de/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() Methode


Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Lies **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ruft das Bildfüllformat der Form ab
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt den horizontalen Versatz der Textur auf 20 Punkte
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Siehe auch

* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)