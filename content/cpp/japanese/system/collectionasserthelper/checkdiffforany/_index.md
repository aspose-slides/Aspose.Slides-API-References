---
title: CheckDiffForAny()
second_title: Aspose.Slides for C++ API リファレンス
description: 任意のコレクション要素が述語に適合するかをチェックします。
type: docs
weight: 27
url: /ja/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) メソッド


任意のコレクション要素が述語に適合することを確認します。

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | チェック対象の述語。 |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | チェック対象の値。 |

### 戻り値

任意の要素でチェックが成功した場合は true、すべての要素が合格した場合は false。

## 関連項目

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [ICollection](../../../system.collections.generic/icollection/)
* 構造体 [CollectionAssertHelper](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)