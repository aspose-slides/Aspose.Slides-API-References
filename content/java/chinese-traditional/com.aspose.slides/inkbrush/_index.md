---
title: InkBrush
second_title: Aspose.Slides for Java API 參考
description: 表示一個 inkBrush 物件。
type: docs
url: /zh-hant/com.aspose.slides/inkbrush/
---
**繼承:**  
java.lang.Object

**所有實作的介面:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

表示一個 inkBrush 物件。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 取得或設定線條的筆刷顏色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 取得或設定線條的筆刷顏色。 |
| [getSize()](#getSize--) | 取得或設定線條的筆刷大小（以點數為單位）。 |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 取得或設定線條的筆刷大小（以點數為單位）。 |
| [getInkEffect()](#getInkEffect--) | 取得墨水效果類型（例如，Galaxy、Gold、Silver），它定義墨跡的視覺樣式。 |

### getColor() {#getColor--}
```
public final Color getColor()
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


**返回:**  
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
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


**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

取得或設定線條的筆刷大小（以點數為單位）。

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
public final void setSize(Dimension2D value)
```

取得或設定線條的筆刷大小（以點數為單位）。

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


**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

取得墨水效果類型（例如，Galaxy、Gold、Silver），它定義墨跡的視覺樣式。此值是從筆刷屬性 "inkEffects" 中解析的。如果未指定已識別的效果，[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) 會被返回。

**返回:**  
int