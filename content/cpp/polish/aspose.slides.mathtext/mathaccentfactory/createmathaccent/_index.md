---
title: CreateMathAccent()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy akcent matematyczny stosowany do określonego elementu matematycznego przy domyślnej wartości znaku akcentu
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metoda

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować akcent |

### Wartość zwracana

nowy akcent matematyczny

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metoda

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
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
* Klasa [MathAccentFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)