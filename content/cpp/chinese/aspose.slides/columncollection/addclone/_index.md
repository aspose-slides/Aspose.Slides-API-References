---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定模板行的副本并将其插入表格的底部。
type: docs
weight: 53
url: /zh/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) 方法


创建指定模板行的副本并将其插入表格的底部。

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 用作模板。 |
| withAttachedColumns | **bool** | True 表示还复制所有附加到模板行的列。 |

### 返回值

已添加的列。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)