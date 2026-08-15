---
title: AddModernComment()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的末尾新增現代評論。
type: docs
weight: 66
url: /zh-hant/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) 方法

在集合的末尾添加新現代評論。

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新現代評論的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 在演示文稿中要添加新現代評論的地方。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 在與新現代評論關聯的投影片上。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在投影片上添加新現代評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 現代評論的建立時間。 |

### 返回值

已添加的現代評論。

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## 另請參閱

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