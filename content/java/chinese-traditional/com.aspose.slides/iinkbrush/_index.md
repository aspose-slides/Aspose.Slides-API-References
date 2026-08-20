---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: 表示軌跡筆刷。
type: docs
url: /zh-hant/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

表示軌跡筆刷。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 取得或設定線條的筆刷顏色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 取得或設定線條的筆刷顏色。 |
| [getSize()](#getSize--) | 取得或設定線條的筆刷尺寸（點數）。 |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 取得或設定線條的筆刷尺寸（點數）。 |
| [getInkEffect()](#getInkEffect--) | 取得墨跡效果類型（例如，Galaxy、Gold、Silver），定義墨跡的視覺樣式。 |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

取得或設定線條的筆刷顏色。

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


**返回：**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

取得或設定線條的筆刷顏色。

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


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

取得或設定線條的筆刷尺寸（點數）。

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

**返回：**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

取得或設定線條的筆刷尺寸（點數）。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

取得墨跡效果類型（例如，Galaxy、Gold、Silver），定義墨跡的視覺樣式。此值從筆刷屬性 "inkEffects" 解析。如果未指定可識別的效果，[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) 會被返回。

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

**返回：**
int