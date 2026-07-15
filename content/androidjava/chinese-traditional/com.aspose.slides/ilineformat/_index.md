---
title: ILineFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示線條的格式。
type: docs
url: /zh-hant/com.aspose.slides/ilineformat/
---
**All Implemented Interfaces:** [com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource) ```
public interface ILineFormat extends ILineParamSource
```

表示線條的格式。
## 方法

| 方法 | 說明 |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Returns true if line format is not defined (as just created, default). |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns or sets the width of a line. |
| [setWidth(double value)](#setWidth-double-) | Returns or sets the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns or sets the line dash style. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Returns or sets the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns or sets the custom dash pattern. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returns or sets the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns or sets the line cap style. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Returns or sets the line cap style. |
| [getStyle()](#getStyle--) | Returns or sets the line style. |
| [setStyle(byte value)](#setStyle-byte-) | Returns or sets the line style. |
| [getAlignment()](#getAlignment--) | Returns or sets the line alignment. |
| [setAlignment(byte value)](#setAlignment-byte-) | Returns or sets the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns or sets the lines join style. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Returns or sets the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns or sets the miter limit of a line. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Returns or sets the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns or sets the arrowhead style at the beginning of a line. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Returns or sets the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns or sets the arrowhead style at the end of a line. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Returns or sets the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns or sets the arrowhead width at the beginning of a line. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Returns or sets the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns or sets the arrowhead width at the end of a line. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Returns or sets the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns or sets the arrowhead length at the beginning of a line. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Returns or sets the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns or sets the arrowhead length at the end of a line. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Returns or sets the arrowhead length at the end of a line. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determines whether the two LineFormat instances are equal. |
| [getEffective()](#getEffective--) | Gets effective line formatting data with the inheritance applied. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```


如果線條格式未定義（剛建立時的預設），則傳回 true。唯讀 boolean。

**傳回：**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```


傳回線條的填充格式。唯讀 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**傳回：**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```


傳回線條的草圖格式。唯讀 [ISketchFormat](../../com.aspose.slides/isketchformat)。

**傳回：**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


傳回或設定線條的寬度。可讀寫 double。

**傳回：**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


傳回或設定線條的寬度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


傳回或設定線條的虛線樣式。可讀寫 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**傳回：**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```


傳回或設定線條的虛線樣式。可讀寫 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


傳回或設定自訂虛線圖案。可讀寫 float[]。

**傳回：**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```


傳回或設定自訂虛線圖案。可讀寫 float[]。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


傳回或設定線條端點樣式。可讀寫 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**傳回：**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```


傳回或設定線條端點樣式。可讀寫 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


傳回或設定線條樣式。可讀寫 [LineStyle](../../com.aspose.slides/linestyle)。

**傳回：**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```


傳回或設定線條樣式。可讀寫 [LineStyle](../../com.aspose.slides/linestyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


傳回或設定線條對齊方式。可讀寫 [LineAlignment](../../com.aspose.slides/linealignment)。

**傳回：**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```


傳回或設定線條對齊方式。可讀寫 [LineAlignment](../../com.aspose.slides/linealignment)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


傳回或設定線條接合樣式。可讀寫 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**傳回：**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```


傳回或設定線條接合樣式。可讀寫 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


傳回或設定線條的斜角限制。可讀寫 float。

**傳回：**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```


傳回或設定線條的斜角限制。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


傳回或設定線條起點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**傳回：**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```


傳回或設定線條起點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


傳回或設定線條終點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**傳回：**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```


傳回或設定線條終點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


傳回或設定線條起點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**傳回：**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```


傳回或設定線條起點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


傳回或設定線條終點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**傳回：**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```


傳回或設定線條終點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


傳回或設定線條起點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**傳回：**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```


傳回或設定線條起點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


傳回或設定線條終點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**傳回：**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```


傳回或設定線條終點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```


判斷兩個 LineFormat 實例是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 要與目前的 LineFormat 比較的 LineFormat。 |

**傳回：**
boolean - **true** 若指定的 LineFormat 等於目前的 LineFormat；否則 **false**。
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```


取得套用繼承後的有效線條格式資料。

**傳回：**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。