---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API 参考
description: 表示描迹画笔。
type: docs
url: /zh/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

表示描迹画笔。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置线条的画笔颜色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 获取或设置线条的画笔颜色。 |
| [getSize()](#getSize--) | 获取或设置线条的画笔大小（单位：点）。 |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | 获取或设置线条的画笔大小（单位：点）。 |
| [getInkEffect()](#getInkEffect--) | 获取墨水效果类型（例如，Galaxy、Gold、Silver），该类型定义墨水笔画的视觉样式。 |

### getColor() {#getColor--}
```
public abstract Integer getColor()
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

**Returns:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
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
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()


获取墨水效果类型（例如，Galaxy、Gold、Silver），该类型定义墨水笔画的视觉样式。该值从画笔属性 "inkEffects" 解析。如果未指定已识别的效果，则返回 [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)。

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**返回值:**
int