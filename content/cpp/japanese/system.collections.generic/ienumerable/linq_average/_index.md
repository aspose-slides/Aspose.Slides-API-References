---
title: LINQ_Average()
second_title: Aspose.Slides for C++ API リファレンス
description: 数値シーケンスの平均を計算します。
type: docs
weight: 365
url: /ja/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() メソッド


数値シーケンスの平均を計算します。

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### 戻り値

シーケンス内の値の平均です。

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) メソッド


入力シーケンスの各要素に変換関数を適用して取得した値のシーケンスの平均を計算します。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| ResultType | selector が返す値の型です。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 各要素に適用する変換関数です。 |

### 戻り値

投影された値の平均です。

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) メソッド


```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## 参照

* クラス [IEnumerable](../)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)