---
title: get_TileFlip()
second_title: Aspose.Slides pro C++ API Reference
description: "Otočí dlaždici textury kolem její vodorovné, svislé nebo obou os. Přečtěte Slides::TileFlip."
type: docs
weight: 404
url: /cs/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metoda


Otočí dlaždici textury kolem její vodorovné, svislé nebo obou os. Číst [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Poznámky


Výchozí hodnota je [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Otočí dlaždici textury kolem její svislé osy.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Viz také

* Enum [TileFlip](../../tileflip/)
* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)