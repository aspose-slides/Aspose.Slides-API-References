---
title: AddModernComment()
second_title: Aspose.Slides の C++ API リファレンス
description: コレクションの末尾に新しいモダンコメントを追加します。
type: docs
weight: 66
url: /ja/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) メソッド


コレクションの末尾に新しいモダンコメントを追加します。

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新しいモダンコメントのプレーンテキスト。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) プレゼンテーション内で新しいモダンコメントを追加する場所。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) 新しいモダンコメントが関連付けられるスライド上の要素。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 新しいモダンコメントを追加するスライド上の位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | モダンコメント作成の時間。 |

### 戻り値

追加されたモダンコメント。

## 注釈




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IModernComment](../../imoderncomment/)
* クラス [String](../../../system/string/)
* クラス [ISlide](../../islide/)
* クラス [IShape](../../ishape/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [DateTime](../../../system/datetime/)
* クラス [CommentCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)