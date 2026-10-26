---
title: IRowCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示表格列集合。
type: docs
url: /zh-hant/com.aspose.slides/irowcollection/
---
**已實作的介面:**  
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

表示表格列集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 建立指定範本列的副本並將其插入表格的底部。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 建立指定範本列的副本並將其插入表格的指定位置。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 從表格的指定位置移除列。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

建立指定範本列的副本並將其插入表格的底部。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | 作為範本使用的列。 |
| withAttachedRows | boolean | True 以複製所有附加於範本列的列。 |

**傳回值:**
com.aspose.slides.IRow[] - 已新增的列。
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

建立指定範本列的副本並將其插入表格的指定位置。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [IRow](../../com.aspose.slides/irow) | 作為範本使用的列。 |
| withAttachedRows | boolean | True 以複製所有附加於範本列的列。 |

**傳回值:**
com.aspose.slides.IRow[] - 已插入的列。
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

從表格的指定位置移除列。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| firstRowIndex | int | 要刪除之列的索引。 |
| withAttachedRows | boolean | True 以刪除所有附加的列。 |