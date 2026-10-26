---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定模板行的副本并将其插入表格的底部。
type: docs
weight: 53
url: /zh/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) 方法

创建指定模板行的副本并将其插入表格的底部。

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作模板。 |
| withAttachedRows | **bool** | True 表示还要复制所有附加到模板行的行。 |

### 返回值

已添加的行。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)