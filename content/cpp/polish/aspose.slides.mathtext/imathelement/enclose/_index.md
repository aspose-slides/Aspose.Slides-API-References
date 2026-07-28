---
title: Enclose()
second_title: Aspose.Slides for C++ – referencja API
description: Otacza element matematyczny w nawiasach
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() metoda

Otacza element matematyczny w nawiasach

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) zawierający nawias

## Uwagi

Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) metoda

Otacza ten element określonymi znakami, takimi jak nawiasy lub innymi znakami, jako ramka

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char16_t | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char16_t | Znak końcowy (zwykle prawy nawias) |

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) zawierający określone znaki jako ramkę

## Uwagi

Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../../imathdelimiter/)
* Klasa [IMathElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)