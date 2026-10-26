---
title: InsertModernComment()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处向集合插入新的现代评论。
type: docs
weight: 92
url: /zh/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) 方法

在指定索引处向集合插入新的现代评论。

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 集合中元素的索引，即应插入现代评论的位置。 |
| text | [System::String](../../../system/string/) | 新现代评论的纯文本。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中用于添加新现代评论的演示文稿。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 在幻灯片上，与新现代评论关联的形状。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在幻灯片上添加新现代评论的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 现代评论创建的时间。 |

### 返回值

已插入的现代评论。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IModernComment](../../imoderncomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [IShape](../../ishape/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)