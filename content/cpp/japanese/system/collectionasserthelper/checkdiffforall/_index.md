---
title: CheckDiffForAll()
second_title: Aspose.Slides for C++ API リファレンス
description: すべてのコレクション要素が述語に適合していることをチェックします。
type: docs
weight: 14
url: /ja/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) メソッド

すべてのコレクション要素が述語に適合していることをチェックします。

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | チェックする述語。 |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | チェックする値。 |

### 戻り値

要素のいずれかでチェックが失敗した場合は false、すべてが合格した場合は true を返します。

## 参照

* typedef [SharedPtr](../../sharedptr/)
* クラス [ICollection](../../../system.collections.generic/icollection/)
* 構造体 [CollectionAssertHelper](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)