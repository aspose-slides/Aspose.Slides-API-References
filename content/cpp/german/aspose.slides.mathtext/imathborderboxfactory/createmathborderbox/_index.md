---
title: CreateMathBorderBox()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein mathematisches Rahmenfeld, indem es auf das Element angewendet wird
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) Methode

Erstellt ein mathematisches Rahmenfeld, indem es auf das Element angewendet wird

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathematisches Element, auf das das Rahmenfeld angewendet wird |

### Rückgabewert

Neues Rahmenfeld-Element

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) Methode

Erstellt ein mathematisches Rahmenfeld, indem es auf das Element angewendet wird

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathematisches Element, auf das das Rahmenfeld angewendet wird |
| hideTop | **bool** | Obere Kante ausblenden |
| hideBottom | **bool** | Untere Kante ausblenden |
| hideLeft | **bool** | Linke Kante ausblenden |
| hideRight | **bool** | Rechte Kante ausblenden |
| strikethroughHorizontal | **bool** | Rahmenfeld Durchgestrichen Horizontal |
| strikethroughVertical | **bool** | Rahmenfeld Durchgestrichen Vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Rahmenfeld Durchgestrichen von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | **bool** | Rahmenfeld Durchgestrichen von oben links nach unten rechts |

### Rückgabewert

Neues Rahmenfeld-Element

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBorderBox](../../imathborderbox/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathBorderBoxFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)