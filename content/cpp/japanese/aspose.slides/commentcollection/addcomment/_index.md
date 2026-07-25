---
title: AddComment()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しいコメントを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

コレクションの末尾に新しいコメントを追加します。

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新しいコメントのプレーンテキスト。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 新しいコメントを追加するプレゼンテーション内の [Slide](../../slide/)。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 新しいコメントを追加するスライド上の位置。 |
| creationTime | [System::DateTime](../../../system/datetime/) | コメント作成時刻。 |

### 戻り値

追加されたコメント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IComment](../../icomment/)
* クラス [String](../../../system/string/)
* クラス [ISlide](../../islide/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [DateTime](../../../system/datetime/)
* クラス [CommentCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)