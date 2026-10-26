---
title: get_TileFlip()
second_title: Aspose.Slides dla C++ - referencja API
description: "Odwraca kafelek tekstury wzdłuż jego osi poziomej, pionowej lub obu jednocześnie. Przeczytaj Slides::TileFlip."
type: docs
weight: 404
url: /pl/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() metoda


Odwraca kafelek tekstury wzdłuż jego osi poziomej, pionowej lub obu jednocześnie. Przeczytaj [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
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

// Odwraca kafelek tekstury wzdłuż osi pionowej.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Zobacz także

* Enum [TileFlip](../../tileflip/)
* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)