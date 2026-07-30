---
title: set_TileOffsetY()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, zatímco záporná hodnota ji posouvá nahoru. Zapište float.
type: docs
weight: 313
url: /cs/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) metoda


Nastavuje vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, zatímco záporná hodnota ji posouvá nahoru. Zapište **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vertikální posun textury na -50 bodů
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Viz také

* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)