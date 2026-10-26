---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定の作者が追加したすべてのスライドコメントを返します。
type: docs
weight: 209
url: /ja/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) メソッド


特定の作者が追加したすべてのスライドコメントを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 検索対象となるコメントの作者、またはすべてのコメントを返す場合は null。 |

### 戻り値

[Comment](../../comment/) の配列。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IComment](../../icomment/)
* クラス [ICommentAuthor](../../icommentauthor/)
* クラス [Slide](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)