---
title: set_TileFlip()
second_title: Aspose.Slides pro C++ API referenci
description: "Překlopí texturovou dlaždici podél její horizontální, vertikální nebo obou os. Zapište Slides::TileFlip."
type: docs
weight: 417
url: /cs/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Překlopí texturovou dlaždici podél její horizontální, vertikální nebo obou os. Zapište [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Poznámky


Výchozí je [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na dlaždice
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Překlopí texturovou dlaždici podél její vertikální osy.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Viz také

* Enum [TileFlip](../../tileflip/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)