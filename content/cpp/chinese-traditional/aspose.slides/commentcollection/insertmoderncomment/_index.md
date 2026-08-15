---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API 參考文件
description: 在集合中於指定索引插入新的現代評論。
type: docs
weight: 92
url: /zh-hant/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) 方法

在集合中於指定索引插入新的現代評論。

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 集合中應插入現代評論的元素索引。 |
| text | [System::String](../../../system/string/) | 新現代評論的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在要加入新現代評論的簡報中。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 在與新現代評論關聯的投影片上。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 投影片上加入新現代評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 新現代評論的建立時間。 |

### 返回值

已插入的現代評論。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IModernComment](../../imoderncomment/)
* 類別 [String](../../../system/string/)
* 類別 [ISlide](../../islide/)
* 類別 [IShape](../../ishape/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [CommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)