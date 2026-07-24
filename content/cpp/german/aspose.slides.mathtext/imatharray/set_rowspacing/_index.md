---
title: set_RowSpacing()
second_title: Aspose.Slides für C++ API-Referenz
description: "Abstand zwischen den Zeilen eines Arrays wird nur verwendet, wenn RowSpacingRule auf 3 Exactly gesetzt ist, in welchem Fall die Maßeinheit Punkte ist, oder auf Multiple, in welchem Fall die Maßeinheit halbe Zeilen ist. Standard: 0"
type: docs
weight: 131
url: /de/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) Methode

Abstand zwischen den Zeilen eines Arrays Wird nur verwendet, wenn RowSpacingRule auf 3 Exactly gesetzt ist, in welchem Fall die Einheit Punkte ist, oder auf Multiple, in welchem Fall die Einheit halbe Zeilen ist. Standard: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
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