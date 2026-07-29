---
title: CreateMathBorderBox()
second_title: Aspose.Slides för C++ API-referens
description: Skapa en matematikram genom att tillämpa på elementet
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metod


Skapa en matematikram genom att tillämpa på elementet

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematiskt element för att tillämpa ram |

### Returvärde

nytt ram-element

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metod


Skapa en matematikram genom att tillämpa på elementet

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematiskt element för att tillämpa ram |
| hideTop | **bool** | Dölj överkant |
| hideBottom | **bool** | Dölj nederkant |
| hideLeft | **bool** | Dölj vänsterkant |
| hideRight | **bool** | Dölj högkant |
| strikethroughHorizontal | **bool** | Genomstrykning horisontell |
| strikethroughVertical | **bool** | Genomstrykning vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Genomstrykning nedre vänstra till övre högra |
| strikethroughTopLeftToBottomRight | **bool** | Genomstrykning övre vänstra till nedre högra |

### Returvärde

nytt ram-element

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBorderBox](../../imathborderbox/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathBorderBoxFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)