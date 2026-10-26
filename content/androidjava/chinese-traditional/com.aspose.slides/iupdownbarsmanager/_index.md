---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 提供對折線圖或股票圖之上/下條的存取。
type: docs
url: /zh-hant/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

提供對折線圖或股票圖之上/下條的存取。
## Methods

| 方法 | 描述 |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | 返回上升條的格式。 |
| [getDownBarsFormat()](#getDownBarsFormat--) | 返回下降條的格式。 |
| [hasUpDownBars()](#hasUpDownBars--) | 判斷圖表是否具有上/下條。 |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | 判斷圖表是否具有上/下條。 |
| [getGapWidth()](#getGapWidth--) | 返回或設定間隙寬度。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 返回或設定間隙寬度。 |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

返回上升條的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回:**  
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

返回下降條的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回:**  
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

判斷圖表是否具有上/下條。可讀寫布林值。

**返回:**  
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

判斷圖表是否具有上/下條。可讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

返回或設定間隙寬度。可讀寫整數。

**返回:**  
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

返回或設定間隙寬度。可讀寫整數。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |