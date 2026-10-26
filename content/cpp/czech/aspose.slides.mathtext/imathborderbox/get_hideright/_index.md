---
title: get_HideRight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Skrytí pravého okraje (výchozí hodnota je false) – určuje stav skrytí nebo zobrazení pravého okraje rámečkového pole.
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/imathborderbox/get_hideright/
---
## IMathBorderBox::get_HideRight() metoda


Skrýt pravý okraj (výchozí hodnota je false) - určuje stav skrytí nebo zobrazení pravého okraje rámečkového pole.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideRight()=0
```

## Poznámky


Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## Viz také

* Třída [IMathBorderBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)