---
title: set_ExplicitBreak()
second_title: Aspose.Slides dla C++ – referencja API
description: "Przerwa jawna określa, czy na początku obiektu Box znajduje się podział linii, tak aby linia zawijała się na początku obiektu Box. Określa liczbę operatora w poprzedniej linii tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącej linii tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (brak jawnej przerwy)"
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metoda

Przerwa jawna określa, czy na początku obiektu Box znajduje się podział linii, tak aby linia zawijała się na początku obiektu Box. Określa liczbę operatora w poprzedniej linii tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącej linii tekstu matematycznego. możliwe wartości: 1..255 Domyślnie: 0 (brak jawnej przerwy)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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