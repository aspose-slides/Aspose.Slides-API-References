---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定模板列的副本并将其插入表格中的指定位置。
type: docs
weight: 66
url: /zh/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) 方法

创建指定模板列的副本并将其插入到表格中的指定位置。

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新列的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 用作模板。 |
| withAttachedColumns | **bool** | True 若为 true，则同时复制所有附加到模板列的列。 |

### 返回值

已插入的列。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IColumn](../../icolumn/)
* 类 [ColumnCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)