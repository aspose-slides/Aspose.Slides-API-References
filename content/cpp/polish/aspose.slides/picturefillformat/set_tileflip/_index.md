---
title: set_TileFlip()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Odwraca kafelek tekstury wokół jego poziomej, pionowej lub obu osi. Zapisz Slides::TileFlip."
type: docs
weight: 417
url: /pl/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metoda


Odwraca kafelek tekstury wokół jego poziomej, pionowej lub obu osi. Zapisz [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Uwagi


Domyślnie jest [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazu kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazu na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Odwraca kafelek tekstury wokół osi pionowej.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Zobacz także

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)