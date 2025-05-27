---
title: IRotation3D
second_title: Aspose.Slides für .NET API Referenz
description: Stellt die 3D-Rotation eines Diagramms dar.
type: docs
weight: 2120
url: /de/aspose.slides.charts/irotation3d/
---

## IRotation3D-Schnittstelle

Stellt die 3D-Rotation eines Diagramms dar.

```csharp
public interface IRotation3D
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DepthPercents](../../aspose.slides.charts/irotation3d/depthpercents) { get; set; } | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). Lese-/Schreibzugriff UInt16. |
| [HeightPercents](../../aspose.slides.charts/irotation3d/heightpercents) { get; set; } | Gibt die Höhe eines 3D-Diagramms als Prozentsatz der Diagrammbreite an (zwischen 5 und 500 Prozent). Lese-/Schreibzugriff UInt16. |
| [Perspective](../../aspose.slides.charts/irotation3d/perspective) { get; set; } | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). Wird ignoriert, wenn der Wert der Eigenschaft RightAngleAxes true ist. Lese-/Schreibzugriff Byte. |
| [RightAngleAxes](../../aspose.slides.charts/irotation3d/rightangleaxes) { get; set; } | Bestimmt, ob die Diagrammachsen rechtwinklig sind oder perspektivisch dargestellt werden. Mit anderen Worten, es bestimmt, ob die Diagrammachsenwinkel unabhängig von der Drehung oder Erhebung des Diagramms sind. Lese-/Schreibzugriff Boolean. |
| [RotationX](../../aspose.slides.charts/irotation3d/rotationx) { get; set; } | Gibt den Rotationsgrad um die X-Achse zurück oder setzt ihn, d.h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option "Y Rotation" in PowerPoint 2007+. Lese-/Schreibzugriff SByte. |
| [RotationY](../../aspose.slides.charts/irotation3d/rotationy) { get; set; } | Gibt den Rotationsgrad um die Y-Achse zurück oder setzt ihn, d.h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option "X Rotation" in PowerPoint 2007+. Lese-/Schreibzugriff UInt16. |

### Siehe Auch

* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->