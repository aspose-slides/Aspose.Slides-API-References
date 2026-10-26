---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Řídí generování SVG tvaru.
type: docs
url: /cs/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Řídí generování SVG tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Tato funkce je volána před vykreslením tvaru do SVG, aby uživatel mohl ovládat výsledné SVG. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

Tato funkce je volána před vykreslením tvaru do SVG, aby uživatel mohl ovládat výsledné SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Objekt pro řízení generování SVG tvaru. |
| shape | [IShape](../../com.aspose.slides/ishape) | Zdrojový tvar. |