---
title: PickPivotAndPartition()
second_title: Aspose.Slides for C++ API リファレンス
description: クイックソート用にピボットを選択し、キーと値のペアを分割します。
type: docs
weight: 105
url: /ja/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 関数

クイックソート用にピボットを選択し、キーと値のペアを分割します。

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 分割するキーのスパン |
| values | [Span](../../system/span/)\<TValue\>\& | 分割する値のスパン |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) キー用の関数 |

### 戻り値

分割後のピボットインデックス

## 関連項目

* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)