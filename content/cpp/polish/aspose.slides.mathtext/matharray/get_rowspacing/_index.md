---
title: get_RowSpacing()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Odstępy między wierszami tablicy. Używany jest tylko wtedy, gdy RowSpacingRule jest ustawiony na 3, dokładnie w takim przypadku jednostką miary są punkty lub Multiple, w którym przypadku jednostką miary są pół-linie. Domyślnie: 0"
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() metoda


Odstępy między wierszami tablicy Używany jest tylko wtedy, gdy RowSpacingRule jest ustawiony na 3 Dokładnie w takim przypadku jednostką miary są punkty lub Multiple, w którym to przypadku jednostką miary są pół-linii. Domyślnie: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
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