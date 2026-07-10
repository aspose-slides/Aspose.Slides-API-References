---
title: IRowCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示表行集合。
type: docs
url: /zh/com.aspose.slides/irowcollection/
---
**已实现的接口:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

表示表行集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 创建指定模板行的副本并将其插入表的底部。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 创建指定模板行的副本并将其插入表中的指定位置。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 从表中删除指定位置的行。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

创建指定模板行的副本并将其插入表的底部。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | 用作模板的行。 |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

**返回值:**
com.aspose.slides.IRow[] - 已添加的行。

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

创建指定模板行的副本并将其插入表中的指定位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新行的索引。 |
| templ | [IRow](../../com.aspose.slides/irow) | 用作模板的行。 |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

**返回值:**
com.aspose.slides.IRow[] - 已插入的行。

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

从表中删除指定位置的行。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstRowIndex | int | 要删除的行的索引。 |
| withAttachedRows | boolean | True to delete also all attached rows. |