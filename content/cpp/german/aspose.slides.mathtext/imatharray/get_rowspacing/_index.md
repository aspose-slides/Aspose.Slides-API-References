---
title: get_RowSpacing()
second_title: Aspose.Slides für C++ API-Referenz
description: "Abstand zwischen den Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Einheit Punkte oder Multiple, in diesem Fall ist die Einheit Halblinien. Standard: 0"
type: docs
weight: 118
url: /de/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() Methode


Abstand zwischen den Zeilen eines Arrays Es wird nur verwendet wenn RowSpacingRule auf 3 gesetzt ist Genau in diesem Fall ist die Maßeinheit Punkte oder Multiple in diesem Fall ist die Maßeinheit Halbzeilen. Standard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Anmerkungen


Beispiel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Siehe auch

* Klasse [IMathArray](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)