---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Java API Reference
description: Styr generering av SVG-former.
type: docs
url: /sv/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Styr generering av SVG-former.
## Metoder

| Method | Description |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Denna funktion anropas innan rendering av formen till SVG för att låta användaren kontrollera den resulterande SVG:n. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


Denna funktion anropas innan rendering av formen till SVG för att låta användaren kontrollera den resulterande SVG:n.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Objekt för att kontrollera SVG-formgenerering. |
| shape | [IShape](../../com.aspose.slides/ishape) | Källform. |