---
title: CreateMathBorderBox()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstelle eine mathematische Randbox, indem sie auf das Element angewendet wird
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) Methode

Erstelle eine mathematische Randbox, indem sie auf das Element angewendet wird

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathe-Element, dem die Randbox hinzugefügt wird |

### Rückgabewert

neues Randbox-Element

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) Methode

Erstelle eine mathematische Randbox, indem sie auf das Element angewendet wird

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathe-Element, dem die Randbox hinzugefügt wird |
| hideTop | **bool** | Obere Kante ausblenden |
| hideBottom | **bool** | Untere Kante ausblenden |
| hideLeft | **bool** | Linke Kante ausblenden |
| hideRight | **bool** | Rechte Kante ausblenden |
| strikethroughHorizontal | **bool** | Horizontale Durchstreichung der Randbox |
| strikethroughVertical | **bool** | Vertikale Durchstreichung der Randbox |
| strikethroughBottomLeftToTopRight | **bool** | Durchstreichung der Randbox von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | **bool** | Durchstreichung der Randbox von oben links nach unten rechts |

### Rückgabewert

neues Randbox-Element

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBorderBox](../../imathborderbox/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBorderBoxFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)