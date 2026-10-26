---
title: CreateMathAccent()
second_title: Aspose.Slides dla referencji API C++
description: Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metoda


Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować akcent |

### Wartość zwracana

nowy akcent matematyczny

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metoda


Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować akcent |
| accentCharacter | char16_t | znak akcentu |

### Wartość zwracana

nowy akcent matematyczny

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathAccent](../../imathaccent/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathAccentFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)