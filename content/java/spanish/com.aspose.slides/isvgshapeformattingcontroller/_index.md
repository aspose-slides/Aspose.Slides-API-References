---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Java API Reference
description: Controls SVG shape generation.
type: docs
url: /es/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Controla la generación de formas SVG.
## Métodos

| Método | Descripción |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Esta función se llama antes de renderizar la forma a SVG para permitir al usuario controlar el SVG resultante. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

Esta función se llama antes de renderizar la forma a SVG para permitir al usuario controlar el SVG resultante.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Objeto para controlar la generación de formas SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma de origen. |