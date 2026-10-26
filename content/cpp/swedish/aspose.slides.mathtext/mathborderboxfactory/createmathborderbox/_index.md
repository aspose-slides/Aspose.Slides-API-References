---
title: CreateMathBorderBox()
second_title: Aspose.Slides för C++ API-referens
description: Skapa en matematisk kantlåda genom att tillämpa på elementet
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metod


Skapa en matematisk kantlåda genom att tillämpa på elementet

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikelement för att tillämpa kantlåda |

### Returvärde

ny kantlådaelement

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metod


Skapa en matematisk kantlåda genom att tillämpa på elementet

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikelement för att tillämpa kantlåda |
| hideTop | **bool** | Dölj överkant |
| hideBottom | **bool** | Dölj nederkant |
| hideLeft | **bool** | Dölj vänsterkant |
| hideRight | **bool** | Dölj högerkant |
| strikethroughHorizontal | **bool** | Kantlåda Genomstrykning Horisontell |
| strikethroughVertical | **bool** | Kantlåda Genomstrykning Vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Kantlåda Genomstrykning Nedre vänster till övre höger |
| strikethroughTopLeftToBottomRight | **bool** | Kantlåda Genomstrykning Övre vänster till nedre höger |

### Returvärde

ny kantlådaelement

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBorderBox](../../imathborderbox/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBorderBoxFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)