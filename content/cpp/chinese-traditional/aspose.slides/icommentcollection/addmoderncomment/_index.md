---
title: AddModernComment()
second_title: Aspose.Slides for C++ API 參考文件
description: 在集合的末端新增現代評論。
type: docs
weight: 27
url: /zh-hant/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


在集合的末尾新增現代評論。

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新現代評論的純文字。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 在投影片中，[Slide](../../slide/) 用於新增現代評論的地方。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 在投影片上，[Shape](../../shape/) 為新現代評論所關聯的。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 在投影片上新增現代評論的位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | 現代評論的建立時間。 |

### 返回值

已新增的現代評論。
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
* 類別 [IModernComment](../../imoderncomment/)
* 類別 [String](../../../system/string/)
* 類別 [ISlide](../../islide/)
* 類別 [IShape](../../ishape/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [ICommentCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)