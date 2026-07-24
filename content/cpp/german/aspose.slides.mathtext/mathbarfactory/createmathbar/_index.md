---
title: CreateMathBar()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstelle einen Math-Balken, indem er auf das Element angewendet wird.
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) Methode

Erstelle einen Math-Balken, indem er auf das Element angewendet wird.

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Math-Element, auf das der Balken angewendet wird |

### Rückgabewert

neues Math-Balken-Element

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) Methode

Erstelle einen Math-Balken, indem er auf das Element angewendet wird.

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Math-Element, auf das der Balken angewendet wird |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position des Balkens |

### Rückgabewert

neues Math-Balken-Element

## Siehe Auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBar](../../imathbar/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBarFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)