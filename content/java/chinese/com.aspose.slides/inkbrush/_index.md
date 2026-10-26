---
title: InkBrush
second_title: Aspose.Slides Java API 参考
description: 表示一个 inkBrush 对象。
type: docs
url: /zh/com.aspose.slides/inkbrush/
---
**继承:**  
java.lang.Object

**全部已实现的接口:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

表示一个 inkBrush 对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置线条的画笔颜色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 获取或设置线条的画笔颜色。 |
| [getSize()](#getSize--) | 获取或设置线条的画笔大小（单位：点）。 |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 获取或设置线条的画笔大小（单位：点）。 |
| [getInkEffect()](#getInkEffect--) | 获取墨水效果类型（例如，Galaxy、Gold、Silver），定义墨水笔划的视觉样式。 |

### getColor() {#getColor--}
```
public final Color getColor()
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

**返回值:**  
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
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
public final Dimension2D getSize()
```

获取或设置线条的画笔大小（单位：点）。

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

**返回值:**  
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

获取或设置线条的画笔大小（单位：点）。

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
public final int getInkEffect()
```

获取墨水效果类型（例如，Galaxy、Gold、Silver），定义墨水笔划的视觉样式。该值是从画笔属性 "inkEffects" 解析得到的。如果未指定已识别的效果，将返回 [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)。

**返回值:**  
int