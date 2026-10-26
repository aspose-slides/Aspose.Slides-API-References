---
title: InsertComment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのコレクションに新しいコメントを挿入します。
type: docs
weight: 40
url: /ja/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) メソッド

指定されたインデックスにコレクションへ新しいコメントを挿入します。

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コメントを挿入すべきコレクション内要素のインデックス。 |
| text | [System::String](../../../system/string/) | 新しいコメントのプレーンテキスト。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) プレゼンテーション内で新しいコメントを追加する場所。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 新しいコメントを追加するスライド上の位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | コメント作成時刻。 |

### 戻り値

挿入されたコメント。

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