---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls SVG shape generation.
type: docs
url: /pl/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Kontroluje generowanie kształtu SVG.
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
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Obiekt do kontrolowania generowania kształtu SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt źródłowy. |