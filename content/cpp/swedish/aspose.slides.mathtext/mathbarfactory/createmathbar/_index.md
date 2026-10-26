---
title: CreateMathBar()
second_title: Aspose.Slides för C++ API-referens
description: Skapa en matematisk stapel genom att applicera på elementet
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) metod


Create a math bar by applying to the element

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | mattelement för att applicera stapel |

### Returvärde

new math bar element

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) metod


Create a math bar by applying to the element

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mattelement för att applicera stapel |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position för stapeln |

### Returvärde

new math bar element

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBar](../../imathbar/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBarFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)