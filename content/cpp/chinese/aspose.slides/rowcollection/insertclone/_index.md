---
title: InsertClone()
second_title: Aspose.Slides for C++ API 参考
description: 创建指定模板行的副本，并将其插入到表格中的指定位置。
type: docs
weight: 66
url: /zh/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) 方法

创建指定模板行的副本，并将其插入到表格中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新行的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作模板。 |
| withAttachedRows | **bool** | True 表示还要复制所有附加到模板行的行。 |

### 返回值

已插入的行。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IRow](../../irow/)
* 类 [RowCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)