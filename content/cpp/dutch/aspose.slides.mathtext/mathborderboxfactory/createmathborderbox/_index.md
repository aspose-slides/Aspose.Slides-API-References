---
title: CreateMathBorderBox()
second_title: Aspose.Slides voor C++ API Referentie
description: Maak een wiskundige randbox door toe te passen op het element
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) methode


Maak een wiskundige randbox door toe te passen op het element

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om randbox toe te passen |

### Retourwaarde

nieuw randbox-element

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) methode


Maak een wiskundige randbox door toe te passen op het element

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om randbox toe te passen |
| hideTop | **bool** | Verberg bovenrand |
| hideBottom | **bool** | Verberg onderrand |
| hideLeft | **bool** | Verberg linkerrand |
| hideRight | **bool** | Verberg rechterrand |
| strikethroughHorizontal | **bool** | Randbox doorhalen horizontaal |
| strikethroughVertical | **bool** | Randbox doorhalen verticaal |
| strikethroughBottomLeftToTopRight | **bool** | Randbox doorhalen van onder links naar boven rechts |
| strikethroughTopLeftToBottomRight | **bool** | Randbox doorhalen van boven links naar onder rechts |

### Retourwaarde

nieuw randbox-element

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBorderBox](../../imathborderbox/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBorderBoxFactory](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)