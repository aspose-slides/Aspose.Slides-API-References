---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls SVG shape generation.
type: docs
url: /nl/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Regelt de generatie van SVG-vormen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Deze functie wordt aangeroepen vóór het renderen van een vorm naar SVG om de gebruiker de controle over het resulterende SVG te geven. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

Deze functie wordt aangeroepen vóór het renderen van een vorm naar SVG om de gebruiker de controle over het resulterende SVG te geven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Object om SVG-vormgeneratie te regelen. |
| shape | [IShape](../../com.aspose.slides/ishape) | Bronvorm. |