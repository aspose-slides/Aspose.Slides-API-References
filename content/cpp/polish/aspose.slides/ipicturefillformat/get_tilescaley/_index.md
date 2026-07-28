---
title: get_TileScaleY()
second_title: Aspose.Slides dla C++ - Referencja API
description: Zwraca pionową skalę wypełnienia teksturą jako procent. Odczyt float.
type: docs
weight: 352
url: /pl/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() metoda


Zwraca pionową skalę wypełnienia teksturą jako wartość procentową. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
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

* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)