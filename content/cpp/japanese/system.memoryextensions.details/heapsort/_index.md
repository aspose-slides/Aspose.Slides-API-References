---
title: HeapSort()
second_title: Aspose.Slides for C++ API リファレンス
description: キーと値のペアに対してヒープソートを実行します。
type: docs
weight: 79
url: /ja/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 関数


キーと値のペアに対してヒープソートを実行します。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| TKey | キーの型 |
| TValue | 値の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ソートするキーのスパン |
| values | [Span](../../system/span/)\<TValue\>\& | ソートする値のスパン |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) キー用の関数 |

## 参照

* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)