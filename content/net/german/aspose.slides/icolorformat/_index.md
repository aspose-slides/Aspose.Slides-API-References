---
title: IColorFormat
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine in einer Präsentation verwendete Farbe dar.
type: docs
weight: 5290
url: /de/aspose.slides/icolorformat/
---

## IColorFormat-Schnittstelle

Stellt eine in einer Präsentation verwendete Farbe dar.

```csharp
public interface IColorFormat : IFillParamSource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/icolorformat/asifillparamsource) { get; } | Gibt die IFillParamSource-Schnittstelle zurück. Nur-Lese [`IFillParamSource`](../ifillparamsource). |
| [B](../../aspose.slides/icolorformat/b) { get; set; } | Gibt die blaue Komponente einer Farbe zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Byte. |
| [Color](../../aspose.slides/icolorformat/color) { get; set; } | Gibt die resultierende Farbe (nach Anwendung aller Farbtransformationen) zurück. Setzt RGB-Farben und löscht alle Farbtransformationen. Lese-/Schreibzugriff Color. |
| [ColorTransform](../../aspose.slides/icolorformat/colortransform) { get; } | Gibt die Sammlung von Farbtransformationen zurück, die auf eine Farbe angewendet werden. Nur-Lese [`IColorOperationCollection`](../icoloroperationcollection). |
| [ColorType](../../aspose.slides/icolorformat/colortype) { get; set; } | Gibt die Farbdefinitionsmethode zurück oder setzt sie. Lese-/Schreibzugriff [`ColorType`](../colortype). |
| [FloatB](../../aspose.slides/icolorformat/floatb) { get; set; } | Gibt die blaue Komponente einer Farbe zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Single. |
| [FloatG](../../aspose.slides/icolorformat/floatg) { get; set; } | Gibt die grüne Komponente einer Farbe zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Single. |
| [FloatR](../../aspose.slides/icolorformat/floatr) { get; set; } | Gibt die rote Komponente einer Farbe zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Single. |
| [G](../../aspose.slides/icolorformat/g) { get; set; } | Gibt die grüne Komponente einer Farbe zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Byte. |
| [Hue](../../aspose.slides/icolorformat/hue) { get; set; } | Gibt die Farbtönungskomponente einer Farbe in HSL-Darstellung zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Single. |
| [Luminance](../../aspose.slides/icolorformat/luminance) { get; set; } | Gibt die Helligkeitskomponente einer Farbe in HSL-Darstellung zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Single. |
| [PresetColor](../../aspose.slides/icolorformat/presetcolor) { get; set; } | Gibt die Farbpräsentation zurück oder setzt sie. Lese-/Schreibzugriff [`PresetColor`](../presetcolor). |
| [R](../../aspose.slides/icolorformat/r) { get; set; } | Gibt die rote Komponente einer Farbe zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Byte. |
| [Saturation](../../aspose.slides/icolorformat/saturation) { get; set; } | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder setzt sie. Alle Farbtransformationen werden ignoriert. Lese-/Schreibzugriff Single. |
| [SchemeColor](../../aspose.slides/icolorformat/schemecolor) { get; set; } | Gibt die durch ein Farbschema identifizierte Farbe zurück oder setzt sie. Lese-/Schreibzugriff [`SchemeColor`](../schemecolor). |
| [SystemColor](../../aspose.slides/icolorformat/systemcolor) { get; set; } | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder setzt sie. Lese-/Schreibzugriff [`SystemColor`](../systemcolor). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CopyFrom](../../aspose.slides/icolorformat/copyfrom)(IColorFormat) | Kopiert das Farbformat von "color". |
| [ToString](../../aspose.slides/icolorformat/tostring)(ColorStringFormat) | Gibt eine Zeichenfolge zurück, die das aktuelle Farbformat darstellt. |

### Siehe auch

* Schnittstelle [IFillParamSource](../ifillparamsource)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->