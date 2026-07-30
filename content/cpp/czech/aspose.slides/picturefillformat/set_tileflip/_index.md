---
title: set_TileFlip()
second_title: Aspose.Slides pro rozhraní API C++
description: "Otočí texturovou dlaždici kolem její horizontální, vertikální nebo obou os. Zapište Slides::TileFlip."
type: docs
weight: 417
url: /cs/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) metoda

Otočí texturovanou dlaždici kolem její horizontální, vertikální nebo obou os. Zapište [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Poznámky

Výchozí hodnota je [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Otočí texturovou dlaždici kolem její vertikální osy.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Viz také

* Enum [TileFlip](../../tileflip/)
* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)