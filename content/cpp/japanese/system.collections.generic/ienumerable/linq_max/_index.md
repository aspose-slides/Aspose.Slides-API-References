---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API リファレンス
description: ジェネリック シーケンスの各要素に変換関数を適用し、結果として得られる最大値を返します。
type: docs
weight: 352
url: /ja/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) メソッド


ジェネリック シーケンスの各要素に変換関数を適用し、結果として得られる最大値を返します。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| ResultType | selector が返す値の型です。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 各要素に適用する変換関数です。 |

### 戻り値

シーケンス内の最大値です。

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) メソッド




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## 参照

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)