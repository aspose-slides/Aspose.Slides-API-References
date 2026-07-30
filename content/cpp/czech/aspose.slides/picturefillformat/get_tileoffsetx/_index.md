---
title: get_TileOffsetX()
second_title: Aspose.Slides pro referenci API C++
description: Vrací horizontální offset textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva. Číst float.
type: docs
weight: 274
url: /cs/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() metoda

Vrací horizontální offset textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva. Číst **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví horizontální offset textury na 20 bodů
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)