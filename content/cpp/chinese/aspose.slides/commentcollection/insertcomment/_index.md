---
title: InsertComment()
second_title: Aspose.Slides for C++ API 参考
description: 在指定索引处向集合插入新评论。
type: docs
weight: 79
url: /zh/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) 方法

在指定索引处向集合插入新评论。

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 集合中元素的索引，评论应插入的位置。 |
| text | [System::String](../../../system/string/) | 新评论的纯文本。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 在演示文稿中[Slide](../../slide/)，用于添加新评论。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 幻灯片上添加新评论的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 评论创建的时间。 |

### 返回值

已插入的评论。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IComment](../../icomment/)
* 类 [String](../../../system/string/)
* 类 [ISlide](../../islide/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [DateTime](../../../system/datetime/)
* 类 [CommentCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)