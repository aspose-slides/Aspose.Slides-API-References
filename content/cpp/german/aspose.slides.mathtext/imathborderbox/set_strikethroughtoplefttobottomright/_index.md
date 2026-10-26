---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides für C++ API Referenz
description: Durchgestrichen von oben links nach unten rechts (Standard ist false). Gibt den verborgenen oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmenkastens an.
type: docs
weight: 209
url: /de/aspose.slides.mathtext/imathborderbox/set_strikethroughtoplefttobottomright/
---
## IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) Methode

Strikethrough Top-Left to Bottom-Right (default is false). Gibt den verborgenen oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmenkastens an.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value)=0
```

## Hinweise

Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## Siehe auch

* Klasse [IMathBorderBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)