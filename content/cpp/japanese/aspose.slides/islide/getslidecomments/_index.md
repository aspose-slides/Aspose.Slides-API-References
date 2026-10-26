---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定の作者が追加したすべてのスライドコメントを返します。
type: docs
weight: 118
url: /ja/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) メソッド


特定の作者が追加したすべてのスライドコメントを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | 検索対象のコメント作者、またはすべてのコメントを返す場合は null。 |

### 戻り値

[IComment](../../icomment/) の配列。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentAuthor](../../icommentauthor/)
* Class [ISlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)