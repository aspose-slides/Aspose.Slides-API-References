---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Java API Reference
description: Steruje generowaniem kształtu SVG.
type: docs
url: /pl/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Steruje generowaniem kształtu SVG.

## Metody

| Metoda | Opis |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Ta funkcja jest wywoływana przed renderowaniem kształtu do SVG, aby umożliwić użytkownikowi kontrolowanie wynikowego SVG. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

Ta funkcja jest wywoływana przed renderowaniem kształtu do SVG, aby umożliwić użytkownikowi kontrolowanie wynikowego SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Obiekt służący do kontrolowania generowania kształtu SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt źródłowy. |