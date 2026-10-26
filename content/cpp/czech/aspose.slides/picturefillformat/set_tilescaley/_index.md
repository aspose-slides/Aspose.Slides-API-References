---
title: set_TileScaleY()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje vertikální měřítko výplně texturou jako procento. Zapište float.
type: docs
weight: 365
url: /cs/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metoda


Nastavuje vertikální měřítko pro výplň texturou jako procento. Zapište **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Poznámky


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vertikální měřítko textury na 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)