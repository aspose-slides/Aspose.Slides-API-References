---
title: get_TileFlip()
second_title: Aspose.Slides dla C++ – referencja API
description: "Odwraca płytkę tekstury wokół jej poziomej, pionowej lub obu osi. Przeczytaj Slides::TileFlip."
type: docs
weight: 404
url: /pl/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metoda

Odwraca płytkę tekstury wokół jej poziomej, pionowej lub obu osi. Przeczytaj [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Uwagi

Domyślnie jest [TileFlip::NoFlip](../../tileflip/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Obraca płytkę tekstury wokół jej pionowej osi.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Zobacz także

* Wyliczenie [TileFlip](../../tileflip/)
* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)