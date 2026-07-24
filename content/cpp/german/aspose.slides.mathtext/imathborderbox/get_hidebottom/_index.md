---
title: get_HideBottom()
second_title: Aspose.Slides für C++ API-Referenz
description: Untere Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an.
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() Methode

Hide Bottom Edge (Standardwert ist false) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## Anmerkungen

Beispiel:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## Siehe auch

* Klasse [IMathBorderBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)