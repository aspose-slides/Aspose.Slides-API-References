---
title: InkBrush
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 inkBrush 对象。
type: docs
url: /zh/com.aspose.slides/inkbrush/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

表示一个 inkBrush 对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置线条的画笔颜色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 获取或设置线条的画笔颜色。 |
| [getSize()](#getSize--) | 获取或设置线条的画笔大小（单位：点）。 |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | 获取或设置线条的画笔大小（单位：点）。 |
| [getInkEffect()](#getInkEffect--) | 获取墨迹效果类型（例如：Galaxy、Gold、Silver），该类型定义了墨迹笔画的视觉样式。 |

### getColor() {#getColor--}
```
public final Integer getColor()
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
public final void setColor(Integer value)
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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
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
> ```

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
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
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
获取墨迹效果类型（例如：Galaxy、Gold、Silver），该类型定义了墨迹笔画的视觉样式。该值从 brush 属性 "inkEffects" 中解析。如果未指定已识别的效果，[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) 将被返回。  

**返回:**  
int