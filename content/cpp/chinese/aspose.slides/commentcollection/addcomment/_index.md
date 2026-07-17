---
title: AddComment()
second_title: Aspose.Slides C++ API 参考
description: 在集合的末尾添加新评论。
type: docs
weight: 53
url: /zh/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) 方法

在集合末尾添加新评论。

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新评论的纯文本。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中添加新评论的地点。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在幻灯片上添加新评论的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 评论创建的时间。 |

### 返回值

添加的评论。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IComment](../../icomment/)
* 类 [String](../../../system/string/)
* 类 [ISlide](../../islide/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [DateTime](../../../system/datetime/)
* 类 [CommentCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)