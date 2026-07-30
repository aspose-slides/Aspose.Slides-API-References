---
title: get_TileScaleX()
second_title: Aspose.Slides pro C++ - reference API
description: Vrací horizontální měřítko výplně texturou jako procento. Číst float.
type: docs
weight: 326
url: /cs/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() metoda


Vrací horizontální měřítko výplně texturou jako procento. Číst **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví horizontální měřítko textury na 120 procent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Viz také

* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)