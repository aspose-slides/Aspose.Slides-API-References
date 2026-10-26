---
title: get_TileScaleY()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací vertikální měřítko texturové výplně jako procento. Čte float.
type: docs
weight: 352
url: /cs/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metoda

Vrací vertikální měřítko pro texturové vyplnění jako procento. Čte **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vertikální měřítko textury na 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)