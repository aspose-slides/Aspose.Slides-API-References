---
title: CreateMathBar()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří matematický pruh aplikací na prvek
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) metoda

Vytvoří matematický pruh aplikací na prvek

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje pruh |

### Návratová hodnota

nový prvek matematického pruhu

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) metoda

Vytvoří matematický pruh aplikací na prvek

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Matematický prvek, na který se aplikuje pruh |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozice pruhu |

### Návratová hodnota

nový prvek matematického pruhu

## Viz také

* Výčet [MathTopBotPositions](../../mathtopbotpositions/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBar](../../imathbar/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathBarFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)