---
title: set_TileOffsetX()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten fest. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Schreiben float.
type: docs
weight: 287
url: /de/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) Methode


Legt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten fest. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Schreiben **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ermittelt das Bildfüllformat der Form
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Setzt den Bildfüllmodus auf Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Setzt den horizontalen Versatz der Textur auf 20 Punkte
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Siehe auch

* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)