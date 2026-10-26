---
title: Enclose()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Otacza elementy potomne tego bloku określonymi znakami, takimi jak nawiasy lub inne znaki jako ramka
type: docs
weight: 222
url: /pl/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) metoda


Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) który zawiera określone znaki jako ramkę
## Uwagi



Przykład: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) metoda


Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub innymi jako ramka i oddziela znakiem separatora

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) który zawiera określone znaki jako ramkę i separator
## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../../imathdelimiter/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)