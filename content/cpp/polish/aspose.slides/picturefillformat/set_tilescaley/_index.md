---
title: set_TileScaleY()
second_title: Aspose.Slides dla C++ – referencja API
description: Ustawia pionową skalę wypełnienia teksturą jako procent. Zapisz float.
type: docs
weight: 365
url: /pl/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metoda


Ustawia pionową skalę wypełnienia teksturą jako procent. Zapisz **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazem kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ustawia pionową skalę tekstury na 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Zobacz także

* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)