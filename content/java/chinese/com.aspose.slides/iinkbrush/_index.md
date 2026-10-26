---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: 表示跟踪画笔。
type: docs
url: /zh/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

表示跟踪画笔。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置线条的画笔颜色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 获取或设置线条的画笔颜色。 |
| [getSize()](#getSize--) | 获取或设置线条的画笔大小（以点为单位）。 |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 获取或设置线条的画笔大小（以点为单位）。 |
| [getInkEffect()](#getInkEffect--) | 获取墨水效果类型（例如 Galaxy、Gold、Silver），该类型定义墨水笔触的视觉样式。 |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

获取或设置线条的画笔颜色。

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

**返回:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

获取或设置线条的画笔颜色。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

获取或设置线条的画笔大小（以点为单位）。

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

**返回:**  
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

获取或设置线条的画笔大小（以点为单位）。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

获取墨水效果类型（例如 Galaxy、Gold、Silver），该类型定义墨水笔触的视觉样式。如果未指定已识别的效果，[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) 将被返回。

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

**返回:**  
int