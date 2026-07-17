---
title: AddModernComment()
second_title: Aspose.Slides C++ API 参考
description: 在集合的末尾添加新的现代评论。
type: docs
weight: 27
url: /zh/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method

在集合的末尾添加新的现代评论。

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新现代评论的纯文本。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中用于添加新现代评论的。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 在幻灯片上，用于关联新现代评论。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在幻灯片上添加新现代评论的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 现代评论创建的时间。 |

### 返回值

已添加的现代评论。

## 备注

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## 参见

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