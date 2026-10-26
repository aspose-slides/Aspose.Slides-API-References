---
title: get_TileScaleY()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací svislé měřítko výplně texturou jako procento. Čte se float.
type: docs
weight: 352
url: /cs/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() metoda


Vrací svislé měřítko výplně texturou jako procento. Čte se **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Poznámky


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví svislé měřítko textury na 120 procent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Viz také

* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)