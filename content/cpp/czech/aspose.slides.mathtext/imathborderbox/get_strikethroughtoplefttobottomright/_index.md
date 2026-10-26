---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přeškrtnutí z levého horního rohu do pravého dolního (výchozí hodnota je false). Určuje skrytý nebo zobrazený stav úhlopříčné čáry přeškrtnutí od levého horního rohu k pravému dolnímu rohu border boxu.
type: docs
weight: 196
url: /cs/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() metoda


Přeškrtnutí z levého horního rohu do pravého dolního (výchozí je false). Určuje skrytý nebo zobrazený stav úhlopříčné čáry přeškrtnutí od levého horního rohu k pravému dolnímu rohu border boxu.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
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