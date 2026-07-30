---
title: set_TileScaleX()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje horizontální měřítko texturové výplně v procentech. Zapište float.
type: docs
weight: 339
url: /cs/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) metoda


Nastavuje horizontální měřítko texturové výplně v procentech. Zapište **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
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