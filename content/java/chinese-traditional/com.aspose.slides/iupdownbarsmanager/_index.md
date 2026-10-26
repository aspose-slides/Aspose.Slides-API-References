---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /zh-hant/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

提供對線圖或股票圖的上/下條形的存取。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | 返回上條形的格式。 |
| [getDownBarsFormat()](#getDownBarsFormat--) | 返回下條形的格式。 |
| [hasUpDownBars()](#hasUpDownBars--) | 判斷圖表是否具有上/下條形。 |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | 判斷圖表是否具有上/下條形。 |
| [getGapWidth()](#getGapWidth--) | 返回或設定間隙寬度。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 返回或設定間隙寬度。 |

### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

返回上條形的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**回傳:**
[IFormat](../../com.aspose.slides/iformat)

### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

返回下條形的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**回傳:**
[IFormat](../../com.aspose.slides/iformat)

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

判斷圖表是否具有上/下條形。可讀寫 boolean。

**回傳:**
boolean

### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

判斷圖表是否具有上/下條形。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

返回或設定間隙寬度。可讀寫 int。

**回傳:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

返回或設定間隙寬度。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |