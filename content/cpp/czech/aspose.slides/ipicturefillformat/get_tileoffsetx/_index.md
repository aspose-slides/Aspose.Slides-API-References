---
title: get_TileOffsetX()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva. Čte float.
type: docs
weight: 274
url: /cs/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() metoda


Vrací vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva. Čte **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Poznámky


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vodorovný posun textury na 20 bodů
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Viz také

* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)