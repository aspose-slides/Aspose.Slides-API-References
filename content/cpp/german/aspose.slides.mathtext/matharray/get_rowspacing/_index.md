---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API Referenz
description: "Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 Exactly gesetzt ist, wobei die Maßeinheit Punkte ist, oder auf Multiple, wobei die Maßeinheit Halbzeilen ist. Standard: 0"
type: docs
weight: 118
url: /de/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() Methode

Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 Exactly gesetzt ist, wobei die Maßeinheit Punkte ist, oder auf Multiple, wobei die Maßeinheit Halbzeilen ist. Standard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Hinweise

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