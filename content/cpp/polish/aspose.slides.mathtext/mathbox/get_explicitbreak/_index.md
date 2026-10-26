---
title: get_ExplicitBreak()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: "Jawne łamanie określa, czy na początku obiektu Box występuje podział wiersza, tak aby wiersz zawijał się na początku obiektu Box. Określa liczbę operatora w poprzednim wierszu tekstu matematycznego, która ma być użyta jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (brak jawnego łamania)"
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metoda

Jawne łamanie określa, czy na początku obiektu Box występuje podział wiersza, tak aby wiersz zawijał się na początku obiektu Box. Określa liczbę operatora w poprzednim wierszu tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (brak jawnego łamania)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
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