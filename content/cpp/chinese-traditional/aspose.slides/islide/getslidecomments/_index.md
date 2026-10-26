---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API 參考
description: 傳回由特定作者新增的所有投影片評論。
type: docs
weight: 118
url: /zh-hant/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) 方法

返回由特定作者添加的所有投影片評論。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 要查找的評論作者，或為 null 以返回所有評論。 |

### 回傳值

[IComment](../../icomment/) 陣列。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IComment](../../icomment/)
* 類別 [ICommentAuthor](../../icommentauthor/)
* 類別 [ISlide](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)