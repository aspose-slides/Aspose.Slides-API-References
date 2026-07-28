---
title: Enclose()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Umieszcza elementy podrzędne tego bloku w określonych znakach, takich jak nawiasy lub inne, jako ramy i oddziela je znakiem separatora
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) metoda

Umieszcza elementy podrzędne tego bloku w określonych znakach, takich jak nawiasy lub inne, jako ramy i oddziela je znakiem separatora

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char16_t | Początkowy znak (zazwyczaj lewy nawias) |
| endingCharacter | char16_t | Końcowy znak (zazwyczaj prawy nawias) |
| separatorCharacter | char16_t | Znak separatora |

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) zawierający określone znaki jako ramy i separator
## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../../imathdelimiter/)
* Klasa [IMathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)