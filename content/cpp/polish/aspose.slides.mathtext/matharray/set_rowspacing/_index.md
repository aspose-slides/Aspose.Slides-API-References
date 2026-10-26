---
title: set_RowSpacing()
second_title: Odwołanie do API Aspose.Slides dla C++
description: "Odstępy między wierszami tablicy są używane tylko wtedy, gdy RowSpacingRule jest ustawiony na 3. Dokładnie w takim przypadku jednostką miary są punkty lub Multiple, w którym jednostką miary są półwiersze. Domyślnie: 0"
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) metoda

Odstępy między wierszami tablicy Jest używany tylko wtedy, gdy RowSpacingRule jest ustawiony na 3 Dokładnie w tym przypadku jednostką miary są punkty lub Multiple, w którym to przypadku jednostką miary są półwiersze. Domyślnie: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Uwagi


Przykład: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Zobacz także

* Klasa [MathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)