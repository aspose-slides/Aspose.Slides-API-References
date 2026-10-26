---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides for C++ API リファレンス
description: 比較条件が満たされた場合にキーと値のペアを入れ替えます。
type: docs
weight: 53
url: /ja/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) function

比較条件が満たされた場合にキーと値のペアを入れ替えます。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | キーの型 |
| TValue | 値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | キーのスパン |
| values | [Span](../../system/span/)\<TValue\>\& | 値のスパン |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 関数（キー用） |
| i | **int32_t** | 比較する最初のインデックス |
| j | **int32_t** | 比較する 2 番目のインデックス |

## See Also

* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)