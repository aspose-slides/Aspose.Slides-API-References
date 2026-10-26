---
title: set_TileOffsetX()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, zatímco záporná hodnota ji posouvá doleva. Zapište float.
type: docs
weight: 287
url: /cs/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) metoda

Nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, zatímco záporná hodnota ji posouvá doleva. Zapište **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázku na dlaždice
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vodorovný posun textury na 20 bodů
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Viz také

* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)