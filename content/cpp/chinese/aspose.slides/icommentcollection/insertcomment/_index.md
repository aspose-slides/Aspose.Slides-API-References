---
title: InsertComment()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处向集合插入新评论。
type: docs
weight: 40
url: /zh/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

在指定索引处向集合插入新评论。

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 集合中应插入评论的元素索引。 |
| text | [System::String](../../../system/string/) | 新评论的纯文本。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中添加新评论的幻灯片。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在幻灯片上添加新评论的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 评论创建的时间。 |

### 返回值

已插入的评论。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)