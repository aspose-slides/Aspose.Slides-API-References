---
title: IMathBorderBox
second_title: Aspose.Slides für .NET-API-Referenz
description: Zeichnet einen rechteckigen oder anderen Rahmen um das IMathElement.
type: docs
weight: 7490
url: /de/aspose.slides.mathtext/imathborderbox/
---
## IMathBorderBox interface

Zeichnet einen rechteckigen oder anderen Rahmen um das IMathElement.

```csharp
public interface IMathBorderBox : IMathElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathborderbox/asimathelement) { get; } | Ermöglicht das Abrufen von Basis-IMathElement interface [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathborderbox/base) { get; } | Basisargument |
| [HideBottom](../../aspose.slides.mathtext/imathborderbox/hidebottom) { get; set; } | Untere Kante ausblenden (Standard ist „false“) – gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmens an. |
| [HideLeft](../../aspose.slides.mathtext/imathborderbox/hideleft) { get; set; } | Hide Left Edge (der Standardwert ist „false“) – gibt den ausgeblendeten oder angezeigten Zustand des linken Rands des Rahmens an. |
| [HideRight](../../aspose.slides.mathtext/imathborderbox/hideright) { get; set; } | Rechte Kante ausblenden (Standard ist „false“) – gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmens an. |
| [HideTop](../../aspose.slides.mathtext/imathborderbox/hidetop) { get; set; } | Obere Kante ausblenden (Standard ist „false“) – gibt den ausgeblendeten oder angezeigten Zustand der Oberkante des Rahmens an. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/imathborderbox/strikethroughbottomlefttotopright) { get; set; } | Von unten links nach oben rechts durchgestrichen (Standardwert ist „false“). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Rahmenfelds an. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/imathborderbox/strikethroughhorizontal) { get; set; } | Durchgestrichene horizontale Linie (Standardeinstellung ist „false“) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/imathborderbox/strikethroughtoplefttobottomright) { get; set; } | Oben links durchgestrichen nach unten rechts (Standardwert ist „false“). Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmenfelds an. |
| [StrikethroughVertical](../../aspose.slides.mathtext/imathborderbox/strikethroughvertical) { get; set; } | Durchgestrichene vertikale Linie (Standardeinstellung ist „false“) – gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an. |

### Beispiele

Beispiel:

```csharp
[C#]
IMathBorderBox borderBox = new MathematicalText("x+y+z").ToBorderBox();
```

### Siehe auch

* interface [IMathElement](../imathelement)
* namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
