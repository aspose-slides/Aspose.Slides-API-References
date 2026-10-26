---
title: IMarker
second_title: Aspose.Slides for Android via Java API Reference
description: Represents marker of a chert.
type: docs
url: /zh-hant/com.aspose.slides/imarker/
---```
public interface IMarker
```

表示圖表的標記。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getSymbol()](#getSymbol--) | 表示折線圖、散點圖或雷達圖中的標記樣式。 |
| [setSymbol(int value)](#setSymbol-int-) | 表示折線圖、散點圖或雷達圖中的標記樣式。 |
| [getFormat()](#getFormat--) | 取得標記的填充。 |
| [getSize()](#getSize--) | 表示折線圖、散點圖或雷達圖中的標記大小。 |
| [setSize(int value)](#setSize-int-) | 表示折線圖、散點圖或雷達圖中的標記大小。 |

### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

表示折線圖、散點圖或雷達圖中的標記樣式。可讀寫 [MarkerStyleType](../../com.aspose.slides/markerstyletype)。

**傳回值:**  
int

### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

表示折線圖、散點圖或雷達圖中的標記樣式。可讀寫 [MarkerStyleType](../../com.aspose.slides/markerstyletype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

取得標記的填充。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**傳回值:**  
[IFormat](../../com.aspose.slides/iformat)

### getSize() {#getSize--}
```
public abstract int getSize()
```

表示折線圖、散點圖或雷達圖中的標記大小。可讀寫 int。

**傳回值:**  
int

### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

表示折線圖、散點圖或雷達圖中的標記大小。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |