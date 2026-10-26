---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls SVG shape generation.
type: docs
url: /sv/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Kontrollerar SVG-formsgenerering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Denna funktion kallas innan rendering av form till SVG för att låta användaren kontrollera den resulterande SVG:n. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


Denna funktion kallas innan rendering av form till SVG för att låta användaren kontrollera den resulterande SVG:n.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Objekt för att kontrollera SVG-formsgenerering. |
| shape | [IShape](../../com.aspose.slides/ishape) | Källform. |