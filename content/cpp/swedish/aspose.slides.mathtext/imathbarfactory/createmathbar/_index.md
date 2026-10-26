---
title: CreateMathBar()
second_title: Aspose.Slides för C++ API-referens
description: Skapa en matematisk stapel genom att applicera på elementet
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) metod


Skapa ett matematiskt stapel genom att applicera på elementet

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematisk element för att applicera stapel |

### Returvärde

nytt math bar-element

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) metod


Skapa ett matematiskt stapel genom att applicera på elementet

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematisk element för att applicera stapel |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | position för stapeln |

### Returvärde

nytt math bar-element

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBar](../../imathbar/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathBarFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)