---
title: AddComment()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 在集合的末尾新增評論。
type: docs
weight: 53
url: /zh-hant/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

在集合的末尾新增評論。

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新評論的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在簡報中，用於新增評論。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在投影片上新增評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 評論建立的時間。 |

### 回傳值

已新增的評論。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComment](../../icomment/)
* 類別 [String](../../../system/string/)
* 類別 [ISlide](../../islide/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [CommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)