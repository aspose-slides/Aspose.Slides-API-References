---
title: CreateMathBar()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstelle einen mathematischen Balken, indem er auf das Element angewendet wird
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) method

Erstelle einen mathematischen Balken, indem er auf das Element angewendet wird

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathematisches Element, auf das der Balken angewendet wird |

### Rückgabewert

neues mathematisches Balkenelement

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) method

Erstelle einen mathematischen Balken, indem er auf das Element angewendet wird

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathematisches Element, auf das der Balken angewendet wird |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position des Balkens |

### Rückgabewert

neues mathematisches Balkenelement

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBar](../../imathbar/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathBarFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)