---
title: LINQ_Min()
second_title: Aspose.Slides for C++ API リファレンス
description: ジェネリック シーケンスの各要素に変換関数を適用し、結果として得られる最小値を返します。
type: docs
weight: 339
url: /ja/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) メソッド

ジェネリック シーケンスの各要素に変換関数を適用し、結果として得られる最小値を返します。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| ResultType | selector が返す値の型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 各要素に適用する変換関数。 |

### 戻り値

シーケンス内の最小値。

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) メソッド




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## 関連項目

* クラス [Func](../../../system/func/)
* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)