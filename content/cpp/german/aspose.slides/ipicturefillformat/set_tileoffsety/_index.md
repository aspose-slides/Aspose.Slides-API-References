---
title: set_TileOffsetY()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten fest. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Schreiben Sie float.
type: docs
weight: 313
url: /de/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) Methode

Setzt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Schreiben Sie **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Anmerkungen



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

* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)