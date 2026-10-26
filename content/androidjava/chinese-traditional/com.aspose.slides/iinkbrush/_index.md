---
title: IInkBrush
second_title: Aspose.Slides for Android Java API 參考
description: 代表痕跡筆刷。
type: docs
url: /zh-hant/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

代表痕跡筆刷。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 取得或設定線條的筆刷顏色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 取得或設定線條的筆刷顏色。 |
| [getSize()](#getSize--) | 取得或設定線條的筆刷大小（以點為單位）。 |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | 取得或設定線條的筆刷大小（以點為單位）。 |
| [getInkEffect()](#getInkEffect--) | 取得墨跡效果類型（例如 Galaxy、Gold、Silver），以定義墨跡筆劃的視覺樣式。 |

### getColor() {#getColor--}
```
public abstract Integer getColor()
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

**回傳:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


取得或設定線條的筆刷大小（以點為單位）。

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


**回傳:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```


取得或設定線條的筆刷大小（以點為單位）。

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
public abstract int getInkEffect()
```


取得墨跡效果類型（例如 Galaxy、Gold、Silver），以定義墨跡筆劃的視覺樣式。此值會從筆刷屬性「inkEffects」解析。若未指定可辨識的效果，將回傳 [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)。

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

**回傳:**
int