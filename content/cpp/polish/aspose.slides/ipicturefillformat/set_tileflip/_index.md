---
title: set_TileFlip()
second_title: Aspose.Slides dla C++ referencja API
description: "Odwraca kafelek tekstury wokół jego poziomej, pionowej lub obu osi. Zapisz Slides::TileFlip."
type: docs
weight: 417
url: /pl/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metoda


Odwraca kafelek tekstury wokół jego poziomej, pionowej lub obu osi. Zapisz [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Uwagi


Domyślna wartość to [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera format wypełnienia obrazem kształtu
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ustawia tryb wypełnienia obrazem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Odwraca kafelek tekstury wokół osi pionowej.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Zobacz także

* Wyliczenie [TileFlip](../../tileflip/)
* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)