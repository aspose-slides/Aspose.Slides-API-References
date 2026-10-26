---
title: set_RowSpacing()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Odstęp między wierszami tablicy. Jest używany tylko wtedy, gdy RowSpacingRule jest ustawiony na 3 - w takim przypadku jednostką miary są punkty lub Multiple - w takim przypadku jednostką miary są pół-linie. Domyślnie: 0"
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) metoda

Odległość między wierszami tablicy. Jest używana tylko wtedy, gdy RowSpacingRule jest ustawiony na 3 - w takim przypadku jednostką miary są punkty lub Multiple - w takim przypadku jednostką miary są pół-linie. Domyślnie: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Uwagi


Przykład: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Zobacz także

* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)