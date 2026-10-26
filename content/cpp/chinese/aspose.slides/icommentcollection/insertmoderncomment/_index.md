---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API 参考
description: 在指定索引处向集合插入新的现代批注。
type: docs
weight: 53
url: /zh/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

在指定索引处向集合插入新的现代批注。

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 集合中元素的索引，即应插入现代批注的位置。 |
| text | [System::String](../../../system/string/) | 新现代批注的纯文本。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中用于添加新现代批注。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 在幻灯片上，与新现代批注关联。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在幻灯片上添加新现代批注的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 现代批注创建的时间。 |

### 返回值

已插入的现代批注。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IModernComment](../../imoderncomment/)
* 类 [String](../../../system/string/)
* 类 [ISlide](../../islide/)
* 类 [IShape](../../ishape/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [DateTime](../../../system/datetime/)
* 类 [ICommentCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)