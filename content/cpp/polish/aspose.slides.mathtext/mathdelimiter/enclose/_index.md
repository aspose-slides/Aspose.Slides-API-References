---
title: Enclose()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zamknięcie elementu matematycznego w określonych znakach, takich jak nawiasy lub inne znaki jako ramka
type: docs
weight: 170
url: /pl/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) metoda

Zamknięcie elementu matematycznego w określonych znakach, takich jak nawiasy lub inne znaki jako ramka

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char16_t | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char16_t | Znak końcowy (zwykle prawy nawias) |

### Wartość zwracana

Jeśli *beginningCharacter* i *endingCharacter* są null, odpowiednie właściwości otrzymują tylko wartości i nie jest tworzony nowy obiekt (zwraca tę instancję). W przeciwnym razie zwraca nowy element matematyczny typu Delimiter, który zawiera określone znaki jako ramkę i tę instancję [MathDelimiter](../) umieszczoną wewnątrz.

## Uwagi

Przykład: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../../imathdelimiter/)
* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)