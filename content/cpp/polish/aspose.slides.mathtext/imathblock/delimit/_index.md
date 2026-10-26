---
title: Delimit()
second_title: Aspose.Slides dla C++ – referencja API
description: Oddziela wszystkie elementy podrzędne znakiem separatora (bez nawiasów)
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) metoda


Oddziela wszystkie elementy potomne znakiem separatora (bez nawiasów)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char16_t | Znak używany jako separator |

### Wartość zwracana

Instancja elementu [IMathDelimiter](../../imathdelimiter/)
## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../../imathdelimiter/)
* Klasa [IMathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)