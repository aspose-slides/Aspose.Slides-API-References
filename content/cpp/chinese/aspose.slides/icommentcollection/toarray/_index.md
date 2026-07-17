---
title: ToArray()
second_title: Aspose.Slides C++ API 参考
description: 创建并返回包含所有注释的数组。
type: docs
weight: 66
url: /zh/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() 方法

创建并返回包含所有注释的数组。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### 返回值

[IComment](../../icomment/) 数组。

## ICommentCollection::ToArray(int32_t, int32_t) 方法

创建并返回指定范围内所有注释的数组。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要返回的第一个注释的索引。 |
| count | **int32_t** | 要返回的注释数量。 |

### 返回值

[IComment](../../icomment/) 数组。

## 另请参阅

* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IComment](../../icomment/)
* 类 [ICommentCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)