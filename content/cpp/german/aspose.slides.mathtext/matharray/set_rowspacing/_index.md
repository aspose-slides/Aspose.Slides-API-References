---
title: set_RowSpacing()
second_title: Aspose.Slides für C++ API-Referenz
description: "Abstand zwischen den Zeilen eines Arrays. Es wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist, genau in diesem Fall ist die Maßeinheit Punkte oder Multiple, in dem Fall ist die Maßeinheit Halbe-Zeilen. Standard: 0"
type: docs
weight: 131
url: /de/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) Methode

Abstand zwischen den Zeilen eines Arrays. Es wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist, genau in diesem Fall ist die Maßeinheit Punkte oder Multiple, in dem Fall ist die Maßeinheit Halbe-Zeilen. Standard: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Bemerkungen

Beispiel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Siehe auch

* Klasse [MathArray](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)