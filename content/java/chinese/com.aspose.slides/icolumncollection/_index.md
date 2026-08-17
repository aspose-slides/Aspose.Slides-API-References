---
title: IColumnCollection
second_title: Aspose.Slides for Java API 参考
description: 表示表格中的列集合。
type: docs
url: /zh/com.aspose.slides/icolumncollection/
---
**所有已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

表示表格中的列集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的列。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 创建指定模板行的副本并将其插入到表格底部。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 创建指定模板列的副本并将其插入到表格中指定位置。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 删除表格中指定位置的列。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


返回指定索引处的列。只读 [IColumn](../../com.aspose.slides/icolumn)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


创建指定模板行的副本并将其插入到表格底部。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的列。 |
| withAttachedColumns | boolean | True 若为 True，则还会复制所有附加到模板行的列。 |

**返回值:**
com.aspose.slides.IColumn[] - 已添加的列。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


创建指定模板列的副本并将其插入到表格中指定位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的列。 |
| withAttachedColumns | boolean | True 若为 True，则还会复制所有附加到模板列的列。 |

**返回值:**
com.aspose.slides.IColumn[] - 已插入的列。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


删除表格中指定位置的列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstColumnIndex | int | 要删除的列的索引。 |
| withAttachedRows | boolean | True 若为 True，则还会删除所有附加的列。 |