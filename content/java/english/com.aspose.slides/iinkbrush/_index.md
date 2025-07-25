---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Represents trace brush.
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Gets or sets the brush color for a line. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gets or sets the brush color for a line. |
| [getSize()](#getSize--) | Gets or sets the brush size for a line in points. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Gets or sets the brush size for a line in points. |
| [getInkEffect()](#getInkEffect--) | Gets the ink effect type (e.g., Galaxy, Gold, Silver) that defines the visual style of the ink stroke. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Gets or sets the brush color for a line.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Gets or sets the brush color for a line.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Gets or sets the brush size for a line in points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


Gets or sets the brush size for a line in points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Gets the ink effect type (e.g., Galaxy, Gold, Silver) that defines the visual style of the ink stroke. The value is parsed from the brush property "inkEffects". If no recognized effect is specified, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) is returned.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
