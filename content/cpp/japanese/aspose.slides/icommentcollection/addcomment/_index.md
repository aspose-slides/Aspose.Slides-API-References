---
title: AddComment()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しいコメントを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) メソッド

コレクションの末尾に新しいコメントを追加します。

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新しいコメントのプレーンテキスト。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) プレゼンテーション内で新しいコメントを追加する場所。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | スライド上で新しいコメントを追加する位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | コメント作成の時刻。 |

### 戻り値

追加されたコメント。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IComment](../../icomment/)
* クラス [String](../../../system/string/)
* クラス [ISlide](../../islide/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [DateTime](../../../system/datetime/)
* クラス [ICommentCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)