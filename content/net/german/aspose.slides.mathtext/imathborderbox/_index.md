---
title: IMathBorderBox
second_title: Aspose.Slides für .NET API Referenz
description: Zeichnet einen rechteckigen oder einen anderen Rahmen um das IMathElement.
type: docs
weight: 7920
url: /de/aspose.slides.mathtext/imathborderbox/
---

## IMathBorderBox-Schnittstelle

Zeichnet einen rechteckigen oder einen anderen Rahmen um das IMathElement.

```csharp
public interface IMathBorderBox : IMathElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathborderbox/asimathelement) { get; } | Ermöglicht den Zugriff auf die Basis-IMathElement-Schnittstelle [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathborderbox/base) { get; } | Basisargument |
| [HideBottom](../../aspose.slides.mathtext/imathborderbox/hidebottom) { get; set; } | Unterkante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmens an. |
| [HideLeft](../../aspose.slides.mathtext/imathborderbox/hideleft) { get; set; } | Linke Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Rahmens an. |
| [HideRight](../../aspose.slides.mathtext/imathborderbox/hideright) { get; set; } | Rechte Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmens an. |
| [HideTop](../../aspose.slides.mathtext/imathborderbox/hidetop) { get; set; } | Obere Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Rahmens an. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/imathborderbox/strikethroughbottomlefttotopright) { get; set; } | Durchstreichung von unten links nach oben rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Rahmens an. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/imathborderbox/strikethroughhorizontal) { get; set; } | Horizontale Durchstreichung (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand einer horizontalen durchgestrichenen Linie an. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/imathborderbox/strikethroughtoplefttobottomright) { get; set; } | Durchstreichung von oben links nach unten rechts (Standard ist false). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmens an. |
| [StrikethroughVertical](../../aspose.slides.mathtext/imathborderbox/strikethroughvertical) { get; set; } | Vertikale Durchstreichung (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand einer vertikalen durchgestrichenen Linie an. |

### Beispiele

Beispiel:

```csharp
[C#]
IMathBorderBox borderBox = new MathematicalText("x+y+z").ToBorderBox();
```

### Siehe auch

* Schnittstelle [IMathElement](../imathelement)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->