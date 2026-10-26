---
title: CreateMathBar()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Utwórz pasek matematyczny, stosując go do elementu
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) metoda

Utwórz pasek matematyczny, stosując go do elementu

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego ma zostać zastosowany pasek |

### Wartość zwracana

nowy element paska matematycznego

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) metoda

Utwórz pasek matematyczny, stosując go do elementu

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element matematyczny, do którego ma zostać zastosowany pasek |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozycja paska |

### Wartość zwracana

nowy element paska matematycznego

## Zobacz także

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBar](../../imathbar/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathBarFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)