---
title: get_TileScaleX()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací vodorovné měřítko výplně texturou jako procento. Čte se jako float.
type: docs
weight: 326
url: /cs/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metoda

Vrací vodorovné měřítko výplně texturou jako procento. Čtení **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Poznámky


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
// Nastaví režim výplně obrázkem na Tile
// Nastaví vodorovné měřítko textury na 120 procent
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the horizontal scale for the texture to 120 percents
pictureFillFormat->set_TileScaleX(120.0f);
```

## Viz také

* třída [PictureFillFormat](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)