---
title: ToArray()
second_title: Aspose.Slides C++ API リファレンス
description: すべてのコメントを含む配列を作成し、返します。
type: docs
weight: 66
url: /ja/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() メソッド

すべてのコメントを含む配列を作成して返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### 戻り値

[IComment](../../icomment/) の配列。

## ICommentCollection::ToArray(int32_t, int32_t) メソッド

指定された範囲のすべてのコメントを含む配列を作成して返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 返す最初のコメントのインデックス。 |
| count | **int32_t** | 返すコメントの数。 |

### 戻り値

[IComment](../../icomment/) の配列。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)