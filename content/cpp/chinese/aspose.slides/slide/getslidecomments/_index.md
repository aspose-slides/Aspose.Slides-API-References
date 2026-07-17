---
title: GetSlideComments()
second_title: Aspose.Slides C++ API 参考
description: 返回特定作者添加的所有幻灯片备注。
type: docs
weight: 209
url: /zh/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) 方法

返回特定作者添加的所有幻灯片备注。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 要查找的评论的作者，或为 null 时返回所有评论。 |

### 返回值

[Comment](../../comment/) 的数组。

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IComment](../../icomment/)
* 类 [ICommentAuthor](../../icommentauthor/)
* 类 [Slide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)