---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API 參考
description: 返回特定作者新增的所有投影片註解。
type: docs
weight: 209
url: /zh-hant/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) 方法

返回特定作者新增的所有投影片註解。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 要查找的註解作者，或為 null 時返回所有註解。 |

### 返回值

[Comment](../../comment/) 陣列。

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComment](../../icomment/)
* 類別 [ICommentAuthor](../../icommentauthor/)
* 類別 [Slide](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)