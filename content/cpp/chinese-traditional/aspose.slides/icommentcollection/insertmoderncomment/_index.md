---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API 參考
description: 在指定索引處向集合插入新的現代評論。
type: docs
weight: 53
url: /zh-hant/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


在指定索引處向集合插入新的現代評論。

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 集合中元素的索引，用於插入現代評論的位置。 |
| text | [System::String](../../../system/string/) | 新現代評論的純文字內容。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在簡報中添加新現代評論的位置。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 在投影片上與新現代評論相關聯。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 投影片上添加新現代評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 現代評論的建立時間。 |

### 回傳值

插入的現代評論。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IModernComment](../../imoderncomment/)
* 類別 [String](../../../system/string/)
* 類別 [ISlide](../../islide/)
* 類別 [IShape](../../ishape/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [ICommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)