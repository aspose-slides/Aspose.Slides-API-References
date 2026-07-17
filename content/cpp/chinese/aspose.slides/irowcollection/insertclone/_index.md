---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定模板行的副本并将其插入表格中指定的位置。
type: docs
weight: 27
url: /zh/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) 方法

创建指定模板行的副本并将其插入表格中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新行的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作模板。 |
| withAttachedRows | **bool** | True 表示也复制所有附加到模板行的行。 |

### 返回值

已插入的行。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IRow](../../irow/)
* 类 [IRowCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)