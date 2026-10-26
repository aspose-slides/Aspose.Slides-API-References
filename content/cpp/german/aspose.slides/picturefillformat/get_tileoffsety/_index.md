---
title: get_TileOffsetY()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Lese float.
type: docs
weight: 300
url: /de/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() Methode

Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Lesen **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Bemerkungen


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt den vertikalen Versatz der Textur auf -50 Punkte
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Siehe auch

* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)