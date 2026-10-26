---
title: MathBorderBox()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt MathBorderBox-Element mit rechteckigem Rand
type: docs
weight: 222
url: /de/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) Konstruktor

Erstellt [MathBorderBox](../) Element mit rechteckigem Rand

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Basiselement, auf das die Randbox angewendet wird. Kann null sein. |

## Bemerkungen



Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) Konstruktor

Erstellt [MathBorderBox](../) Element

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Basiselement, auf das die Randbox angewendet wird |
| hideTop | **bool** | Obere Kante ausblenden |
| hideBottom | **bool** | Untere Kante ausblenden |
| hideLeft | **bool** | Linke Kante ausblenden |
| hideRight | **bool** | Rechte Kante ausblenden |
| strikethroughHorizontal | **bool** | Horizontale Durchstreichung |
| strikethroughVertical | **bool** | Vertikale Durchstreichung |
| strikethroughBottomLeftToTopRight | **bool** | Durchstreichung von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | **bool** | Durchstreichung von oben links nach unten rechts |

## Bemerkungen



Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBorderBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)