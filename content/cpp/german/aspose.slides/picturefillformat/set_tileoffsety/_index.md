---
title: set_TileOffsetY()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten fest. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Schreiben float.
type: docs
weight: 313
url: /de/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) Methode

Legt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten fest. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Schreiben **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical offset of the texture to -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Siehe auch

* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)