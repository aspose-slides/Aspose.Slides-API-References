---
title: set_TileOffsetY()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nastaví svislý posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, zatímco záporná hodnota ji posouvá nahoru. Zapište float.
type: docs
weight: 313
url: /cs/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metoda


Nastaví svislý posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, zatímco záporná hodnota ji posouvá nahoru. Zapište **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázkem tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na dlaždice
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví svislý posun textury na -50 bodů
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)