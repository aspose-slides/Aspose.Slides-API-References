---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのコレクションに新しいモダンコメントを挿入します。
type: docs
weight: 92
url: /ja/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) メソッド

指定されたインデックスのコレクションに新しいモダンコメントを挿入します。

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コレクション内の要素のインデックスで、modern comment を挿入する位置です。 |
| text | [System::String](../../../system/string/) | 新しい modern comment のプレーンテキストです。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) に新しい modern comment を追加するプレゼンテーションです。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 新しい modern comment が関連付けられるスライド上の [Shape](../../shape/) です。 |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | 新しい modern comment を追加するスライド上の位置です。 |
| creationTime | [System::DateTime](../../../system/datetime/) | modern comment の作成時刻です。 |

### 戻り値

挿入された modern comment。

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