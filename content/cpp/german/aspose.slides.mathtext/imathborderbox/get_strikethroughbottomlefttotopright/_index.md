---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides für C++ API-Referenz
description: Durchgestrichener Diagonal von unten links nach oben rechts (Standard ist false). Gibt den verborgenen oder angezeigten Zustand einer durchgestrichenen Diagonallinie von der unteren linken Ecke zur oberen rechten Ecke des Randkastens an.
type: docs
weight: 170
url: /de/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() Methode

Durchgestrichener Diagonal von unten links nach oben rechts (Standard ist false). Gibt den verborgenen oder angezeigten Zustand einer durchgestrichenen Diagonallinie von der unteren linken Ecke zur oberen rechten Ecke des Randkastens an.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Anmerkungen

Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Siehe auch

* Klasse [IMathBorderBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)