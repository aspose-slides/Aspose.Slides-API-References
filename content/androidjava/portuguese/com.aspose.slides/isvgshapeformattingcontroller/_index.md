---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controla a geração de formas SVG.
type: docs
url: /pt/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Controla a geração de formas SVG.
## Métodos

| Método | Descrição |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Esta função é chamada antes da renderização da forma para SVG para permitir que o usuário controle o SVG resultante. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


Esta função é chamada antes da renderização da forma para SVG para permitir que o usuário controle o SVG resultante.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Objeto para controlar a geração da forma SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma de origem. |