---
title: BinarySearch()
second_title: Aspose.Slides for C++ APIリファレンス
description: ソートされた配列で二分探索を実行します。
type: docs
weight: 612
url: /ja/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) メソッド

ソート済み配列に対して二分探索を実行します。

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | 検索を実行するためのソート済み配列 |
| item | const T\& | 検索対象の項目 |

### 戻り値

[Index](../../index/) 検索された項目が見つかった場合はそのインデックス、見つからなかった場合は、検索された項目より大きい次の項目のインデックスのビット単位の補数、または、より大きい項目が存在しない場合は配列の要素数のビット単位の補数です。

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) メソッド

未実装です。

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Array](../)
* クラス [IComparer](../../../system.collections.generic/icomparer/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)