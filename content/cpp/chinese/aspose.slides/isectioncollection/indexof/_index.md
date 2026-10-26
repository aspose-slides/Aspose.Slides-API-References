---
title: IndexOf()
second_title: Aspose.Slides C++ API 参考
description: 返回集合中指定章节的索引。
type: docs
weight: 92
url: /zh/aspose.slides/isectioncollection/indexof/
---
## ISectionCollection::IndexOf(System::SharedPtr\<ISection\>) 方法

返回集合中指定章节的索引。

```cpp
virtual int32_t Aspose::Slides::ISectionCollection::IndexOf(System::SharedPtr<ISection> section)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用于查找。 |

### 返回值

如果章节不在此集合中，则返回 -1；否则返回该章节的索引。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISection](../../isection/)
* 类 [ISectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)