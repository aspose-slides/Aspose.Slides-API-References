---
title: AddComment()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的末尾新增評論。
type: docs
weight: 14
url: /zh-hant/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


在集合的末尾新增評論。

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新評論的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在簡報中要添加新評論的地方。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在投影片上添加新評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 評論建立的時間。 |

### 返回值

已新增的評論。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)