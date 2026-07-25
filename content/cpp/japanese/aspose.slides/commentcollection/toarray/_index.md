---
title: ToArray()
second_title: Aspose.Slides for C++ API リファレンス
description: すべてのコメントを含む配列を作成して返します。
type: docs
weight: 105
url: /ja/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() メソッド

すべてのコメントを含む配列を作成して返します。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### 戻り値

[Comment](../../comment/) の配列。

## CommentCollection::ToArray(int32_t, int32_t) メソッド

指定された範囲のすべてのコメントを含む配列を作成して返します。

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 返される最初のコメントのインデックス。 |
| count | **int32_t** | 返されるコメントの数。 |

### 戻り値

[Comment](../../comment/) の配列。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IComment](../../icomment/)
* クラス [CommentCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)