---
title: LineFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示線條的格式。
type: docs
url: /zh-hant/com.aspose.slides/lineformat/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

表示線條的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | 返回 true，如果線條格式未定義（剛建立時的預設）。 |
| [getFillFormat()](#getFillFormat--) | 返回線條的填充格式。 |
| [getSketchFormat()](#getSketchFormat--) | 返回線條的草圖格式。 |
| [getWidth()](#getWidth--) | 返回或設定線條的寬度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或設定線條的寬度。 |
| [getDashStyle()](#getDashStyle--) | 返回或設定線條的虛線樣式。 |
| [setDashStyle(byte value)](#setDashStyle-byte-) | 返回或設定線條的虛線樣式。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | 返回或設定自訂虛線圖樣。 |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | 返回或設定自訂虛線圖樣。 |
| [getCapStyle()](#getCapStyle--) | 返回或設定線條的端點樣式。 |
| [setCapStyle(byte value)](#setCapStyle-byte-) | 返回或設定線條的端點樣式。 |
| [getStyle()](#getStyle--) | 返回或設定線條樣式。 |
| [setStyle(byte value)](#setStyle-byte-) | 返回或設定線條樣式。 |
| [getAlignment()](#getAlignment--) | 返回或設定線條對齊方式。 |
| [setAlignment(byte value)](#setAlignment-byte-) | 返回或設定線條對齊方式。 |
| [getJoinStyle()](#getJoinStyle--) | 返回或設定線條的接合樣式。 |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | 返回或設定線條的接合樣式。 |
| [getMiterLimit()](#getMiterLimit--) | 返回或設定線條的斜角限制。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 返回或設定線條的斜角限制。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 返回或設定線條起點的箭頭樣式。 |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | 返回或設定線條起點的箭頭樣式。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 返回或設定線條終點的箭頭樣式。 |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | 返回或設定線條終點的箭頭樣式。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 返回或設定線條起點的箭頭寬度。 |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | 返回或設定線條起點的箭頭寬度。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 返回或設定線條終點的箭頭寬度。 |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | 返回或設定線條終點的箭頭寬度。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 返回或設定線條起點的箭頭長度。 |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | 返回或設定線條起點的箭頭長度。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 返回或設定線條終點的箭頭長度。 |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | 返回或設定線條終點的箭頭長度。 |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 判斷兩個 LineFormat 實例是否相等。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效線條格式資料。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long。

**返回:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


與指定的物件比較。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**返回:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


返回 true，如果線條格式未定義（剛建立時的預設）。唯讀  boolean 。

**返回:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


返回線條的填充格式。唯讀 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**返回:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


返回線條的草圖格式。唯讀 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**返回:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


返回或設定線條的寬度。可讀寫  double 。

**返回:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


返回或設定線條的寬度。可讀寫  double 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


返回或設定線條的虛線樣式。可讀寫 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**返回:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


返回或設定線條的虛線樣式。可讀寫 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


返回或設定自訂虛線圖樣。可讀寫  float[] 。

**返回:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


返回或設定自訂虛線圖樣。可讀寫  float[] 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


返回或設定線條的端點樣式。可讀寫 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**返回:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


返回或設定線條的端點樣式。可讀寫 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```


返回或設定線條樣式。可讀寫 [LineStyle](../../com.aspose.slides/linestyle)。

**返回:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


返回或設定線條樣式。可讀寫 [LineStyle](../../com.aspose.slides/linestyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


返回或設定線條對齊方式。可讀寫 [LineAlignment](../../com.aspose.slides/linealignment)。

**返回:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


返回或設定線條對齊方式。可讀寫 [LineAlignment](../../com.aspose.slides/linealignment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


返回或設定線條的接合樣式。可讀寫 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**返回:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


返回或設定線條的接合樣式。可讀寫 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


返回或設定線條的斜角限制。可讀寫  float 。

**返回:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


返回或設定線條的斜角限制。可讀寫  float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


返回或設定線條起點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**返回:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


返回或設定線條起點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


返回或設定線條終點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**返回:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


返回或設定線條終點的箭頭樣式。可讀寫 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


返回或設定線條起點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**返回:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


返回或設定線條起點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


返回或設定線條終點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**返回:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


返回或設定線條終點的箭頭寬度。可讀寫 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


返回或設定線條起點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**返回:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


返回或設定線條起點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


返回或設定線條終點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**返回:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


返回或設定線條終點的箭頭長度。可讀寫 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```


判斷兩個 LineFormat 實例是否相等。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 用於與目前的 LineFormat 進行比較的 LineFormat。 |

**返回:**
boolean - **true** 表示指定的 LineFormat 與目前的 LineFormat 相等；否則為 **false**。
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```


取得套用繼承後的有效線條格式資料。

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**返回:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - 一個 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).