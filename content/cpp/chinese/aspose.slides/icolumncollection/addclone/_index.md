---
title: AddClone()
second_title: Aspose.Slides for C++ API 参考
description: 创建指定模板行的副本并将其插入表格的底部。
type: docs
weight: 14
url: /zh/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) 方法

创建指定模板行的副本并将其插入表格的底部。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 用作模板。 |
| withAttachedColumns | **bool** | True 表示也复制附加到模板行的所有列。 |

### 返回值

添加的列。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IColumn](../../icolumn/)
* 类 [IColumnCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)