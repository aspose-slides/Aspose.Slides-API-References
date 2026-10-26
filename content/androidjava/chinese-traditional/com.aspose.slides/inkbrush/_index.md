---
title: InkBrush
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個 inkBrush 物件。
type: docs
url: /zh-hant/com.aspose.slides/inkbrush/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

表示一個 inkBrush 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColor()](#getColor--) | 取得或設定線條的畫筆顏色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 取得或設定線條的畫筆顏色。 |
| [getSize()](#getSize--) | 取得或設定線條的畫筆大小（點）。 |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | 取得或設定線條的畫筆大小（點）。 |
| [getInkEffect()](#getInkEffect--) | 取得墨水效果類型（例如 Galaxy、Gold、Silver），用於定義墨跡的視覺樣式。 |
### getColor() {#getColor--}
```
public final Integer getColor()
```


取得或設定線條的畫筆顏色。

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


取得或設定線條的畫筆顏色。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


取得或設定線條的畫筆大小（點）。

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

**返回值:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


取得或設定線條的畫筆大小（點）。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


取得墨水效果類型（例如 Galaxy、Gold、Silver），用於定義墨跡的視覺樣式。該值來自畫筆屬性 "inkEffects" 的解析結果。如果未指定可辨識的效果，[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) 會被返回。

**返回值:**
int