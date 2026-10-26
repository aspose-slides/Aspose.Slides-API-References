---
title: BinarySearchImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 共通の二分探索実装です。
type: docs
weight: 118
url: /ja/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) 関数

共通の二分探索実装。

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |
| TValue | 検索対象の値の型 |
| TCompareFunc | 比較用の関数型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const TValue\& | 検索対象の値 |
| compareFunc | TCompareFunc | 値とスパンの要素を比較し、**int32_t**（-1、0、1）を返す関数 |

### 戻り値

[Index](../../system/index/)（見つかった要素のインデックス）または挿入位置のビット単位の補数

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)