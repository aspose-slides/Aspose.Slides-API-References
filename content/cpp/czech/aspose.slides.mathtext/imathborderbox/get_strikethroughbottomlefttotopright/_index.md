---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides pro C++ API Reference
description: Přeškrtnutí z levého dolního rohu do pravého horního rohu (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav přeškrtnuté diagonální čáry od levého dolního rohu po pravý horní roh rámečku.
type: docs
weight: 170
url: /cs/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() metoda


Přeškrtnutí z levého dolního rohu do pravého horního rohu (výchozí je false). Určuje skrytý nebo zobrazený stav přeškrtnuté diagonální čáry od levého dolního rohu po pravý horní roh ohraničujícího rámečku.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Poznámky


Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Viz také

* Třída [IMathBorderBox](../)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)