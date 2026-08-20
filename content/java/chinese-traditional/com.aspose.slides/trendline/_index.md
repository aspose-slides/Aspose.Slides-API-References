---
title: Trendline
second_title: Aspose.Slides for Java API 參考文件
description: 類別表示圖表系列的趨勢線
type: docs
url: /zh-hant/com.aspose.slides/trendline/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

類別表示圖表系列的趨勢線  
## Methods

| 方法 | 描述 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | 取得或設定趨勢線的名稱。 |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | 取得或設定趨勢線的名稱。 |
| [getTrendlineType()](#getTrendlineType--) | 取得或設定趨勢線的類型。 |
| [setTrendlineType(int value)](#setTrendlineType-int-) | 取得或設定趨勢線的類型。 |
| [getFormat()](#getFormat--) | 表示趨勢線的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示趨勢線的格式。 |
| [getBackward()](#getBackward--) | 指定趨勢線在被趨勢化系列的資料之前延伸的類別（或散點圖上的單位）數量。 |
| [setBackward(double value)](#setBackward-double-) | 指定趨勢線在被趨勢化系列的資料之前延伸的類別（或散點圖上的單位）數量。 |
| [getForward()](#getForward--) | 指定趨勢線在被趨勢化系列的資料之後延伸的類別（或散點圖上的單位）數量。 |
| [setForward(double value)](#setForward-double-) | 指定趨勢線在被趨勢化系列的資料之後延伸的類別（或散點圖上的單位）數量。 |
| [getIntercept()](#getIntercept--) | 指定趨勢線交叉 y 軸的位置值。 |
| [setIntercept(double value)](#setIntercept-double-) | 指定趨勢線交叉 y 軸的位置值。 |
| [getDisplayEquation()](#getDisplayEquation--) | 指定在圖表上顯示趨勢線的方程式（與 Rsquaredvalue 同一標籤）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 指定在圖表上顯示趨勢線的方程式（與 Rsquaredvalue 同一標籤）。 |
| [getOrder()](#getOrder--) | 指定多項式趨勢線的階次。 |
| [setOrder(byte value)](#setOrder-byte-) | 指定多項式趨勢線的階次。 |
| [getPeriod()](#getPeriod--) | 指定移動平均趨勢線的期間。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 指定移動平均趨勢線的期間。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 指定在圖表上顯示趨勢線的 R 平方值（與方程式同一標籤）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 指定在圖表上顯示趨勢線的 R 平方值（與方程式同一標籤）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示與此趨勢線相關的圖例項目。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 以參數 "text" 中的文字初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含豐富格式的文字。 |
| [getTextFormat()](#getTextFormat--) | 返回文字格式。 |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

取得或設定趨勢線的名稱。讀寫 String。

**返回：**  
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

取得或設定趨勢線的名稱。讀寫 String。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

取得或設定趨勢線的類型。讀寫 [TrendlineType](../../com.aspose.slides/trendlinetype)。

**返回：**  
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

取得或設定趨勢線的類型。讀寫 [TrendlineType](../../com.aspose.slides/trendlinetype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示趨勢線的格式。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**返回：**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示趨勢線的格式。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

指定趨勢線在被趨勢化系列的資料之前延伸的類別（或散點圖上的單位）數量。於散點圖和非散點圖上，該值必須為任何非負值。讀寫 double。

**返回：**  
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

指定趨勢線在被趨勢化系列的資料之前延伸的類別（或散點圖上的單位）數量。於散點圖和非散點圖上，該值必須為任何非負值。讀寫 double。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

指定趨勢線在被趨勢化系列的資料之後延伸的類別（或散點圖上的單位）數量。於散點圖和非散點圖上，該值必須為任何非負值。讀寫 double。

**返回：**  
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

指定趨勢線在被趨勢化系列的資料之後延伸的類別（或散點圖上的單位）數量。於散點圖和非散點圖上，該值必須為任何非負值。讀寫 double。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

指定趨勢線交叉 y 軸的位置值。此屬性僅在趨勢線類型為 exp、linear 或 poly 時受支援。讀寫 double。

**返回：**  
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

指定趨勢線交叉 y 軸的位置值。此屬性僅在趨勢線類型為 exp、linear 或 poly 時受支援。讀寫 double。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

指定在圖表上顯示趨勢線的方程式（與 Rsquaredvalue 同一標籤）。讀寫 boolean。

**返回：**  
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

指定在圖表上顯示趨勢線的方程式（與 Rsquaredvalue 同一標籤）。讀寫 boolean。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

指定多項式趨勢線的階次。對其他趨勢線類型則忽略。值必須介於 2 與 6 之間。讀寫 byte。

**返回：**  
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

指定多項式趨勢線的階次。對其他趨勢線類型則忽略。值必須介於 2 與 6 之間。讀寫 byte。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

指定移動平均趨勢線的期間。對其他趨勢線變體則忽略。值必須介於 2 與 255 之間。讀寫 byte。

**返回：**  
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

指定移動平均趨勢線的期間。對其他趨勢線變體則忽略。值必須介於 2 與 255 之間。讀寫 byte。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

指定在圖表上顯示趨勢線的 R 平方值（與方程式同一標籤）。讀寫 boolean。

**返回：**  
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

指定在圖表上顯示趨勢線的 R 平方值（與方程式同一標籤）。讀寫 boolean。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

表示與此趨勢線相關的圖例項目。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回：**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

以參數 "text" 中的文字初始化 TextFrameForOverriding。若 TextFrameForOverriding 已經初始化，則直接變更其文字。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文字。 |

**返回：**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

可以包含豐富格式的文字。若此屬性不為 null，則此格式化文字會覆寫資料標籤的自動產生文字。資料標籤的自動產生文字是由 ShowSeriesName、ShowValue… 等屬性管理，且以 TextFormatManager.TextFormat 屬性格式化。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回：**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回：**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**  
[IPresentation](../../com.aspose.slides/ipresentation)