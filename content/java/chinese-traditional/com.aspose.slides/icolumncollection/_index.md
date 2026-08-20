---
title: IColumnCollection
second_title: Aspose.Slides for Java API 參考
description: 表示表格中欄位的集合。
type: docs
url: /zh-hant/com.aspose.slides/icolumncollection/
---
**All Implemented Interfaces:**  
com.aspose.slides.IGenericCollection  
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

表示表格中欄位的集合。

## Methods

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的欄位。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 建立指定範本列的副本，並將其插入表格底部。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 建立指定範本欄的副本，並將其插入表格中的指定位置。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 從表格中移除指定位置的欄位。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

傳回指定索引處的欄位。唯讀 [IColumn](../../com.aspose.slides/icolumn)。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

建立指定範本列的副本，並將其插入表格底部。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 作為範本的欄位。 |
| withAttachedColumns | boolean | 若為 true，則同時複製所有附屬於範本列的欄位。 |

**Returns:**
com.aspose.slides.IColumn[] - 已新增的欄位。

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

建立指定範本欄的副本，並將其插入表格中的指定位置。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新欄位的索引。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 作為範本的欄位。 |
| withAttachedColumns | boolean | 若為 true，則同時複製所有附屬於範本欄的欄位。 |

**Returns:**
com.aspose.slides.IColumn[] - 已插入的欄位。

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

從表格中移除指定位置的欄位。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| firstColumnIndex | int | 要刪除的欄位索引。 |
| withAttachedRows | boolean | 若為 true，則同時刪除所有附屬的欄位。 |