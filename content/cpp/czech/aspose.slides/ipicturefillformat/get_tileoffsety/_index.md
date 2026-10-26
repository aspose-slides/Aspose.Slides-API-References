---
title: get_TileOffsetY()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací vertikální odsazení textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, zatímco záporná hodnota ji posouvá nahoru. Číst float.
type: docs
weight: 300
url: /cs/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() metoda


Vrací vertikální odsazení textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, zatímco záporná hodnota ji posouvá nahoru. Číst **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát vyplnění obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim vyplnění obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vertikální odsazení textury na -50 bodů
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Viz také

* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)