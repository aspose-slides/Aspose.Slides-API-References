---
title: set_ExplicitBreak()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Przerwa explicite określa, czy na początku obiektu Box występuje podział wiersza, tak aby wiersz zawijał się na początku obiektu Box. Określa liczbę operatora w poprzednim wierszu tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (brak przerwy explicite)"
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) metoda

Przerwa explicite określa, czy na początku obiektu Box występuje podział wiersza, tak aby wiersz zawijał się na początku obiektu Box. Określa liczbę operatora w poprzednim wierszu tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (brak przerwy explicite)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Uwagi

Przykład:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Zobacz także

* Klasa [MathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)