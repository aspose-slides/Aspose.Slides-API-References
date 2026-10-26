---
title: set_TileScaleX()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje vodorovné měřítko pro vyplnění texturou jako procento. Zapište float.
type: docs
weight: 339
url: /cs/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) metoda


Nastavuje vodorovné měřítko pro vyplnění texturou jako procento. Zapište **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vodorovné měřítko textury na 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)