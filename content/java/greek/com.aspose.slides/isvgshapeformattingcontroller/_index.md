---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Java API Reference
description: Ελέγχει τη δημιουργία σχήματος SVG.
type: docs
url: /el/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Ελέγχει τη δημιουργία σχήματος SVG.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | This function is called before rendering of shape to SVG to allow user to control resulting SVG. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


This function is called before rendering of shape to SVG to allow user to control resulting SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Αντικείμενο για τον έλεγχο της δημιουργίας σχήματος SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα προέλευσης. |