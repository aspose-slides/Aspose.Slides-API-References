---
title: IRow
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示表格中的一行。
type: docs
url: /zh-hant/com.aspose.slides/irow/
---
**All Implemented Interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

表示表格中的一行。

## Methods

| 方法 | 說明 |
| --- | --- |
| [getHeight()](#getHeight--) | 傳回一行的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 傳回或設定一行的最小可能高度。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 傳回或設定一行的最小可能高度。 |
| [getRowFormat()](#getRowFormat--) | 傳回包含此行格式屬性的 RowFormat 物件。 |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

傳回一行的高度。唯讀 double。

**傳回：**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

傳回或設定一行的最小可能高度。可讀寫 double。

**傳回：**
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

傳回或設定一行的最小可能高度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

傳回包含此行格式屬性的 RowFormat 物件。唯讀 [IRowFormat](../../com.aspose.slides/irowformat)。

**傳回：**
[IRowFormat](../../com.aspose.slides/irowformat)