---
title: ToArray()
second_title: Aspose.Slides C++ API 参考
description: 创建并返回包含所有注释的数组。
type: docs
weight: 105
url: /zh/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() 方法

Creates and returns an array with all comments.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### 返回值

[Comment](../../comment/) 的数组。

## CommentCollection::ToArray(int32_t, int32_t) 方法

Creates and returns an array with all comments from the specified range.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要返回的第一个注释的索引。 |
| count | **int32_t** | 要返回的注释数量。 |

### 返回值

[Comment](../../comment/) 的数组。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IComment](../../icomment/)
* 类 [CommentCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)