---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přeškrtnutí z levého horního rohu do pravého dolního rohu (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav úhlopříčné čáry přeškrtnutí z levého horního rohu do pravého dolního rohu hraničního rámečku.
type: docs
weight: 209
url: /cs/aspose.slides.mathtext/imathborderbox/set_strikethroughtoplefttobottomright/
---
## IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) metoda

Přeškrtnutí z levého horního rohu do pravého dolního rohu (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav úhlopříčné čáry přeškrtnutí z levého horního rohu do pravého dolního rohu ohraničovacího rámečku.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value)=0
```

## Poznámky

Příklad:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## Viz také

* Třída [IMathBorderBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)