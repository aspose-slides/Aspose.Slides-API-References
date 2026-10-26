---
title: Heapify()
second_title: Aspose.Slides for C++ API リファレンス
description: キーと値のペアに対してヒープ属性を維持します。
type: docs
weight: 92
url: /ja/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


キーと値のペアに対してヒープ属性を維持します。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TKey | キーの型 |
| TValue | 値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ヒープ内のキーのスパン |
| values | [Span](../../system/span/)\<TValue\>\& | ヒープ内の値のスパン |
| n | **int32_t** | ヒープのサイズ |
| i | **int32_t** | [Index](../../system/index/) ヒープ化開始位置 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) キー用関数 |

## 参照

* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)