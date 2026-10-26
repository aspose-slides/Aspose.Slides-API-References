---
title: IColumn
second_title: Aspose.Slides for Android via Java API 參考
description: 表示表格中的欄位。
type: docs
url: /zh-hant/com.aspose.slides/icolumn/
---
**所有已實作的介面：**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

表示表格中的欄位。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getWidth()](#getWidth--) | 傳回或設定欄位的寬度。 |
| [setWidth(double value)](#setWidth-double-) | 傳回或設定欄位的寬度。 |
| [getColumnFormat()](#getColumnFormat--) | 傳回包含此欄位格式屬性的 ColumnFormat 物件。 |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


傳回或設定欄位的寬度。讀寫 double.

**傳回：**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


傳回或設定欄位的寬度。讀寫 double.

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


傳回包含此欄位格式屬性的 ColumnFormat 物件。唯讀 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**傳回：**
[IColumnFormat](../../com.aspose.slides/icolumnformat)