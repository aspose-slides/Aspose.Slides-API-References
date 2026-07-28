---
title: Delimit()
second_title: Aspose.Slides dla C++ Referencja API
description: Rozdziela elementy potomne przy użyciu znaku separatora (bez nawiasów)
type: docs
weight: 209
url: /pl/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) metoda

Delimits child elements with separator character (without the brackets)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char16_t | Znak separatora |

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/)

## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../../imathdelimiter/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)