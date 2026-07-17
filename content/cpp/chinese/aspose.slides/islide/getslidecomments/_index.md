---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API 参考
description: 返回特定作者添加的所有幻灯片批注。
type: docs
weight: 118
url: /zh/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) method


返回特定作者添加的所有幻灯片批注。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 要查找的批注的作者，或为 null 时返回所有批注。 |

### 返回值

[IComment](../../icomment/) 的数组。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IComment](../../icomment/)
* 类 [ICommentAuthor](../../icommentauthor/)
* 类 [ISlide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)