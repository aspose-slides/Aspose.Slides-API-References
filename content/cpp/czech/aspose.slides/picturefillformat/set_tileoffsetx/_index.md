---
title: set_TileOffsetX()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví horizontální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, zatímco záporná hodnota ji posouvá doleva. Zapište float.
type: docs
weight: 287
url: /cs/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) metoda

Stanoví horizontální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, zatímco záporná hodnota ji posouvá doleva. Zapište **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Poznámky


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví horizontální posun textury na 20 bodů
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)