---
title: AddClone()
second_title: Aspose.Slides for C++ API 参考
description: 创建指定模板行的副本并将其插入表格的底部。
type: docs
weight: 14
url: /zh/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) method

创建指定模板行的副本并将其插入表格底部。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作模板。 |
| withAttachedRows | **bool** | True 表示也复制附加到模板行的所有行。 |

### 返回值

已添加的行。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)