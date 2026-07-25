---
title: IntroSort()
second_title: Aspose.Slides for C++ API リファレンス
description: キーと値のペアに対するイントロソートアルゴリズムの内部実装です。
type: docs
weight: 40
url: /ja/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function

キーと値のペアに対するイントロソートアルゴリズムの内部実装です。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | キーの型 |
| TValue | 値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ソート対象のキーのスパン |
| values | [Span](../../system/span/)\<TValue\>\& | ソート対象の値のスパン |
| depthLimit | **int32_t** | ヒープソートに切り替える前の最大再帰深度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) キー用の関数 |

## 参照

* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)