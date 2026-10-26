---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變的物件，包含有效的線條格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

不可變的物件，包含有效的線條格式屬性。

--------------------

此介面與 [ILineFormat](../../com.aspose.slides/ilineformat) 介面一起使用，以在套用繼承後返回有效的格式化值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 傳回線條的填充格式。 |
| [getSketchFormat()](#getSketchFormat--) | 傳回線條的草圖格式。 |
| [getWidth()](#getWidth--) | 傳回線條的寬度。 |
| [getDashStyle()](#getDashStyle--) | 傳回線條的虛線樣式。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | 傳回自訂虛線圖樣。 |
| [getCapStyle()](#getCapStyle--) | 傳回線條的端點樣式。 |
| [getStyle()](#getStyle--) | 傳回線條的樣式。 |
| [getAlignment()](#getAlignment--) | 傳回線條的對齊方式。 |
| [getJoinStyle()](#getJoinStyle--) | 傳回線條的連接方式。 |
| [getMiterLimit()](#getMiterLimit--) | 傳回線條的斜接限制。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 傳回線條起點的箭頭樣式。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 傳回線條終點的箭頭樣式。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 傳回線條起點的箭頭寬度。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 傳回線條終點的箭頭寬度。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 傳回線條起點的箭頭長度。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 傳回線條終點的箭頭長度。 |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | 判斷兩個 ILineFormatEffectiveData 實例是否相等。 |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

傳回線條的填充格式。唯讀 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)。

**傳回:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

傳回線條的草圖格式。唯讀 [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)。

**傳回:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

傳回線條的寬度。唯讀 double。

**傳回:**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

傳回線條的虛線樣式。唯讀 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**傳回:**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

傳回自訂虛線圖樣。唯讀 float[]。

**傳回:**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

傳回線條的端點樣式。唯讀 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**傳回:**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

傳回線條的樣式。唯讀 [LineStyle](../../com.aspose.slides/linestyle)。

**傳回:**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

傳回線條的對齊方式。唯讀 [LineAlignment](../../com.aspose.slides/linealignment)。

**傳回:**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

傳回線條的連接方式。唯讀 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**傳回:**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

傳回線條的斜接限制。唯讀 float。

**傳回:**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

傳回線條起點的箭頭樣式。唯讀 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**傳回:**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

傳回線條終點的箭頭樣式。唯讀 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**傳回:**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

傳回線條起點的箭頭寬度。唯讀 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**傳回:**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

傳回線條終點的箭頭寬度。唯讀 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**傳回:**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

傳回線條起點的箭頭長度。唯讀 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**傳回:**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

傳回線條終點的箭頭長度。唯讀 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**傳回:**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

判斷兩個 ILineFormatEffectiveData 實例是否相等。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | 要與目前的 ILineFormatEffectiveData 比較的 ILineFormatEffectiveData。 |

**傳回:**
boolean - **true** 若指定的 ILineFormatEffectiveData 與目前的 ILineFormatEffectiveData 相等；否則，**false**。