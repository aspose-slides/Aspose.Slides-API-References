---
title: AddModernComment()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しいモダンコメントを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) メソッド

コレクションの末尾に新しいモダンコメントを追加します。

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新しいモダンコメントのプレーンテキスト。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) プレゼンテーションで新しいモダンコメントを追加する場所。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) スライド上で新しいモダンコメントに関連付けられる対象。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | スライド上で新しいモダンコメントを追加する位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | モダンコメント作成時刻。 |

### 戻り値

追加されたモダンコメント。

## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IModernComment](../../imoderncomment/)
* クラス [String](../../../system/string/)
* クラス [ISlide](../../islide/)
* クラス [IShape](../../ishape/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [DateTime](../../../system/datetime/)
* クラス [ICommentCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)