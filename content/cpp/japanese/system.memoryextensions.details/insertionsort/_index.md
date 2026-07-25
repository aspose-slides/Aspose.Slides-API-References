---
title: InsertionSort()
second_title: Aspose.Slides for C++ API リファレンス
description: キーと値のペアに対して挿入ソートを実行します。
type: docs
weight: 66
url: /ja/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 関数

キーと値のペアに対して挿入ソートを実行します。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| TKey | キーの型 |
| TValue | 値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ソートするキーのスパン |
| values | [Span](../../system/span/)\<TValue\>\& | ソートする値のスパン |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 関数 キー用 |

## 参照

* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)