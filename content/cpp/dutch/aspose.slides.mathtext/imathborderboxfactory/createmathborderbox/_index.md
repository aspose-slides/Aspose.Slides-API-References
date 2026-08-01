---
title: CreateMathBorderBox()
second_title: Aspose.Slides voor C++ API-referentie
description: Maak een wiskundige randvak door toe te passen op het element
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method


Maak een wiskundige randvak door toe te passen op het element

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om randvak toe te passen |

### Retourwaarde

nieuw randvak element

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method


Maak een wiskundige randvak door toe te passen op het element

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om randvak toe te passen |
| hideTop | **bool** | Verberg bovenrand |
| hideBottom | **bool** | Verberg onderrand |
| hideLeft | **bool** | Verberg linkerrand |
| hideRight | **bool** | Verberg rechterrand |
| strikethroughHorizontal | **bool** | Randvak doorhalen horizontaal |
| strikethroughVertical | **bool** | Randvak doorhalen verticaal |
| strikethroughBottomLeftToTopRight | **bool** | Randvak doorhalen van onderlinks naar bovenrechts |
| strikethroughTopLeftToBottomRight | **bool** | Randvak doorhalen van bovenlinks naar onderrechts |

### Retourwaarde

nieuw randvak element

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBorderBox](../../imathborderbox/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathBorderBoxFactory](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)