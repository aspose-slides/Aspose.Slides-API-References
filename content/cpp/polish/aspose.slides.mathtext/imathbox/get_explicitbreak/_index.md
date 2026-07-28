---
title: get_ExplicitBreak()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Explicit break określa, czy na początku obiektu Box występuje podział wiersza, tak aby linia zawijała się na początku obiektu Box. Określa liczbę operatora w poprzedniej linii tekstu matematycznego, która ma być użyta jako punkt wyrównania dla bieżącej linii tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (no explicit break)"
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metoda


Explicit break określa, czy na początku obiektu Box znajduje się podział wiersza, tak aby wiersz zawijał się na początku obiektu box. Określa liczbę operatora w poprzedniej linii tekstu matematycznego, która ma być użyta jako punkt wyrównania dla bieżącej linii tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (no explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Zobacz także

* Klasa [IMathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)