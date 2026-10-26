---
title: InsertComment()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的指定索引處插入新評論。
type: docs
weight: 40
url: /zh-hant/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

在指定索引處於集合中插入新評論。

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 集合中元素的索引，將在此插入評論。 |
| text | [System::String](../../../system/string/) | 新評論的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 在演示文稿中添加新評論的 [Slide](../../slide/)。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在投影片上添加新評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 評論建立的時間。 |

### 返回值

已插入的評論。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IComment](../../icomment/)
* 類別 [String](../../../system/string/)
* 類別 [ISlide](../../islide/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [ICommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)