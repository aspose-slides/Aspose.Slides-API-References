---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのコレクションに新しいモダンコメントを挿入します。
type: docs
weight: 53
url: /ja/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) メソッド

コレクションの指定されたインデックスに新しいモダン コメントを挿入します。

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | コレクション内の要素のインデックスで、モダン コメントを挿入する位置を指定します。 |
| text | [System::String](../../../system/string/) | 新しいモダン コメントのプレーンテキスト。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 新しいモダン コメントを追加するプレゼンテーション内の[Slide](../../slide/)。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 新しいモダン コメントが関連付けられるスライド上の[Shape](../../shape/)。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 新しいモダン コメントを追加するスライド上の位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | モダン コメントの作成時間。 |

### 戻り値

挿入されたモダン コメント。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IModernComment](../../imoderncomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [IShape](../../ishape/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)