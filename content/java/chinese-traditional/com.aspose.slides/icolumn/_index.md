---
title: IColumn
second_title: Aspose.Slides for Java API 參考
description: 代表表格中的一個欄。
type: docs
url: /zh-hant/com.aspose.slides/icolumn/
---
**已實作的介面：**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

代表表格中的一個欄。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getWidth()](#getWidth--) | 返回或設定欄的寬度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或設定欄的寬度。 |
| [getColumnFormat()](#getColumnFormat--) | 返回包含此欄格式屬性的 ColumnFormat 物件。 |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

返回或設定欄的寬度。可讀寫 double。

**返回值：**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

返回或設定欄的寬度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

返回包含此欄格式屬性的 ColumnFormat 物件。唯讀 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**返回值：**
[IColumnFormat](../../com.aspose.slides/icolumnformat)