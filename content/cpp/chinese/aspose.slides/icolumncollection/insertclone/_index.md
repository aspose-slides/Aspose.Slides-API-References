---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定模板列的副本并将其插入表中指定位置。
type: docs
weight: 27
url: /zh/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) 方法

创建指定模板列的副本并将其插入表中指定位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新列的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | 用作模板的 [Column](../../column/)。 |
| withAttachedColumns | **bool** | 为 true 时，还复制附加到模板列的所有列。 |

### 返回值

已插入的列。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IColumn](../../icolumn/)
* 类 [IColumnCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)