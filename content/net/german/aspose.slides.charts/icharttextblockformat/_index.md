---
title: IChartTextBlockFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt Formatierungseigenschaften für Textelemente in Diagrammen dar.
type: docs
weight: 1900
url: /de/aspose.slides.charts/icharttextblockformat/
---

## IChartTextBlockFormat-Schnittstelle

Stellt Formatierungseigenschaften für Textelemente in Diagrammen dar.

```csharp
public interface IChartTextBlockFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchoringType](../../aspose.slides.charts/icharttextblockformat/anchoringtype) { get; set; } | Gibt den vertikalen Ankertext in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff [`TextAnchorType`](../../aspose.slides/textanchortype). |
| [AutofitType](../../aspose.slides.charts/icharttextblockformat/autofittype) { get; set; } | Gibt den Autofit-Modus des Textes zurück oder setzt ihn. Die Änderung dieser Eigenschaft kann nur Einfluss auf diese Diagrammteile haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Einfluss auf die Darstellung). Lese-/Schreibzugriff [`TextAutofitType`](../../aspose.slides/textautofittype). |
| [CenterText](../../aspose.slides.charts/icharttextblockformat/centertext) { get; set; } | Wenn NullableBool.True, sollte der Text horizontal im Feld zentriert werden. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [MarginBottom](../../aspose.slides.charts/icharttextblockformat/marginbottom) { get; set; } | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Die Änderung dieser Eigenschaft kann nur Einfluss auf diese Diagrammteile haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Einfluss auf die Darstellung). Lese-/Schreibzugriff Double. |
| [MarginLeft](../../aspose.slides.charts/icharttextblockformat/marginleft) { get; set; } | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Die Änderung dieser Eigenschaft kann nur Einfluss auf diese Diagrammteile haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Einfluss auf die Darstellung). Lese-/Schreibzugriff Double. |
| [MarginRight](../../aspose.slides.charts/icharttextblockformat/marginright) { get; set; } | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Die Änderung dieser Eigenschaft kann nur Einfluss auf diese Diagrammteile haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Einfluss auf die Darstellung). Lese-/Schreibzugriff Double. |
| [MarginTop](../../aspose.slides.charts/icharttextblockformat/margintop) { get; set; } | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Die Änderung dieser Eigenschaft kann nur Einfluss auf diese Diagrammteile haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Einfluss auf die Darstellung). Lese-/Schreibzugriff Double. |
| [RotationAngle](../../aspose.slides.charts/icharttextblockformat/rotationangle) { get; set; } | Gibt die benutzerdefinierte Rotation an, die auf den Text innerhalb des begrenzenden Rahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Rotation der begleitenden Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Rotation haben kann, die zusätzlich zur Rotation des Textes selbst angewendet wird. Der resultierende Wert der visuellen Textrrotation setzt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammen. Lese-/Schreibzugriff Single. |
| [TextVerticalType](../../aspose.slides.charts/icharttextblockformat/textverticaltype) { get; set; } | Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textrrotation setzt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammen. Lese-/Schreibzugriff [`TextVerticalType`](../../aspose.slides/textverticaltype). |
| [WrapText](../../aspose.slides.charts/icharttextblockformat/wraptext) { get; set; } | **True**, wenn der Text an den Rändern des TextFrames umgebrochen wird. Die Änderung dieser Eigenschaft kann nur Einfluss auf diese Diagrammteile haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2007/2013). Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |

### Siehe auch

* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)