---
title: IAutoShape
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine AutoShape dar.
type: docs
weight: 5040
url: /de/aspose.slides/iautoshape/
---

## IAutoShape-Schnittstelle

Stellt eine AutoShape dar.

```csharp
public interface IAutoShape : IGeometryShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIGeometryShape](../../aspose.slides/iautoshape/asigeometryshape) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IGeometryShape. Nur lesbar [`IGeometryShape`](../igeometryshape). |
| [AutoShapeLock](../../aspose.slides/iautoshape/autoshapelock) { get; } | Gibt die Sperren der AutoShape zurück. Nur lesbar [`IAutoShapeLock`](../iautoshapelock). |
| [IsTextBox](../../aspose.slides/iautoshape/istextbox) { get; } | Gibt an, ob die Form ein Textfeld ist. |
| [ShapeLock](../../aspose.slides/iautoshape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IAutoShapeLock`](../iautoshapelock). |
| [TextFrame](../../aspose.slides/iautoshape/textframe) { get; } | Gibt das TextFrame-Objekt für die AutoShape zurück. Nur lesbar [`ITextFrame`](../itextframe). |
| [UseBackgroundFill](../../aspose.slides/iautoshape/usebackgroundfill) { get; set; } | Bestimmt, ob diese AutoShape mit der Hintergrundfüllung der Folie anstelle der im Stil oder Füllformat festgelegten Füllung gefüllt werden soll. Lese-/Schreib-Boolean. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTextFrame](../../aspose.slides/iautoshape/addtextframe)(string) | Fügt einer Form ein neues TextFrame hinzu. Wenn die Form bereits ein TextFrame hat, wird einfach dessen Text geändert. |

### Siehe auch

* Schnittstelle [IGeometryShape](../igeometryshape)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->