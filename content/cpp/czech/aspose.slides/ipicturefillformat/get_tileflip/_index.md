---
title: get_TileFlip()
second_title: Aspose.Slides pro referenci API C++
description: "Otočí dlaždici textury kolem její vodorovné, svislé nebo obou os. Přečtěte si Slides::TileFlip."
type: docs
weight: 404
url: /cs/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() metoda


Otočí dlaždici textury kolem její vodorovné, svislé nebo obou os. Přečtěte si [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Poznámky


Výchozí hodnota je [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na dlaždice
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Obrátí texturovou dlaždici podél její svislé osy.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Viz také

* Výčet [TileFlip](../../tileflip/)
* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)