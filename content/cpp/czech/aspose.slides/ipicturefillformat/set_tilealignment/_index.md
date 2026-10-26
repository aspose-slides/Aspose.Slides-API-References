---
title: set_TileAlignment()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a to, jak se opakuje po celém tvaru. Zapište RectangleAlignment.
type: docs
weight: 391
url: /cs/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) metoda


Nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a to, jak se opakuje po celém tvaru. Zapište [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Poznámky


Výchozí je [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá formát výplně obrázku tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví režim výplně obrázkem na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví zarovnání dlaždic na pravý dolní roh
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Viz také

* Výčet [RectangleAlignment](../../rectanglealignment/)
* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)