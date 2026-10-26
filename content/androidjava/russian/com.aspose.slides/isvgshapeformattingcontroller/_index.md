---
title: ISvgShapeFormattingController
second_title: Aspose.Slides для Android через Java API Reference
description: Управляет генерацией SVG-формы.
type: docs
url: /ru/com.aspose.slides/isvgshapeformattingcontroller/
---
```
public interface ISvgShapeFormattingController
```

Управляет генерацией SVG-формы.
## Методы

| Метод | Описание |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Эта функция вызывается перед отрисовкой фигуры в SVG, чтобы пользователь мог управлять полученным SVG. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

Эта функция вызывается перед отрисовкой фигуры в SVG, чтобы пользователь мог управлять полученным SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Объект для управления генерацией SVG-формы. |
| shape | [IShape](../../com.aspose.slides/ishape) | Исходная фигура. |