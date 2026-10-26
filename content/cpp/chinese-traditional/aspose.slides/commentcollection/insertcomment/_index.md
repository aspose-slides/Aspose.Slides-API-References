---
title: InsertComment()
second_title: Aspose.Slides for C++ API 參考
description: 在指定索引處向集合插入新註釋。
type: docs
weight: 79
url: /zh-hant/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


在指定索引處向集合插入新註釋。

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 集合中元素的索引，註釋將被插入於此。 |
| text | [System::String](../../../system/string/) | 新註釋的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中新增註釋的位置。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在投影片上新增註釋的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 註釋建立的時間。 |

### Return Value

已插入的註釋。

## See Also

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComment](../../icomment/)
* 類別 [String](../../../system/string/)
* 類別 [ISlide](../../islide/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [CommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)