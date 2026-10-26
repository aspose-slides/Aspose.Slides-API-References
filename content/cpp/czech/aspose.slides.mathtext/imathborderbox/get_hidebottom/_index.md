---
title: get_HideBottom()
second_title: Aspose.Slides pro C++ API Reference
description: Skrýt spodní okraj (výchozí hodnota je false) – určuje skrytý nebo zobrazený stav spodního okraje rámečku.
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() metoda

Hide Bottom Edge (default is false) - určuje skrytý nebo zobrazený stav spodního okraje rámečku.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## Poznámky

Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## Viz také

* Třída [IMathBorderBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)