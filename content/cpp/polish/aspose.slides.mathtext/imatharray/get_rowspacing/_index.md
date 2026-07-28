---
title: get_RowSpacing()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Odstęp między wierszami tablicy. Jest używany wyłącznie wtedy, gdy RowSpacingRule jest ustawione na 3 Exact, w którym to przypadku jednostką miary są punkty lub Multiple, w którym to jednostką miary są półwiersze. Domyślnie: 0"
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metoda

Odstęp między wierszami tablicy. Jest używany wyłącznie wtedy, gdy RowSpacingRule jest ustawione na 3 Exact, w którym to przypadku jednostką miary są punkty lub Multiple, w którym to przypadku jednostką miary są półwiersze. Domyślnie: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Uwagi

Przykład:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Zobacz także

* Klasa [IMathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)