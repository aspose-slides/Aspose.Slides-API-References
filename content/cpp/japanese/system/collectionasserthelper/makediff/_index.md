---
title: MakeDiff()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つのコレクション間の 'diff' を計算します。各コレクションの各要素をキーとして、要素が "expected" コレクションに多く出現する場合は結果の値が正、"actual" コレクションに多く出現する場合は負、両コレクションで出現回数が同じ場合はゼロになります。
type: docs
weight: 1
url: /ja/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


2つのコレクション間の 'diff' を計算します。各コレクションの各要素をキーとして、要素が "expected" コレクションに多く出現する場合は結果の値が正、"actual" コレクションに多く出現する場合は負、両コレクションで出現回数が同じ場合はゼロになります。

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 期待されるコレクションの要素型。 |
| T2 | 実際のコレクションの要素型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | 期待されるコレクション。 |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | 実際のコレクション。 |

### 戻り値

上記の規則に従った、各値の比較結果のマップ。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Dictionary](../../../system.collections.generic/dictionary/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* 構造体 [CollectionAssertHelper](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)