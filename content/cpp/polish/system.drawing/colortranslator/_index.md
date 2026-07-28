---
title: ColorTranslator
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Wykonuje tłumaczenia kolorów. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 66
url: /pl/system.drawing/colortranslator/
---
## Klasa ColorTranslator

Wykonuje tłumaczenia kolorów. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument.

```cpp
class ColorTranslator
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Konwertuje określoną reprezentację koloru HTML na równoważny obiekt [Color](../color/). |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Konwertuje określony kolor [Windows](../../system.windows/) na równoważny obiekt [Color](../color/). |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Konwertuje określony obiekt [Color](../color/) na ciąg znaków reprezentujący równoważny kolor HTML. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)