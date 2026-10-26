---
title: get_HideLeft()
second_title: Aspose.Slides für C++ API-Referenz
description: Linke Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Border-Box an.
type: docs
weight: 66
url: /de/aspose.slides.mathtext/imathborderbox/get_hideleft/
---
## IMathBorderBox::get_HideLeft() Methode

Hide Left Edge (Standard ist false) - gibt an, ob die linke Kante des border box ausgeblendet oder angezeigt wird.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideLeft()=0
```

## Hinweise

Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## Siehe auch

* Klasse [IMathBorderBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)