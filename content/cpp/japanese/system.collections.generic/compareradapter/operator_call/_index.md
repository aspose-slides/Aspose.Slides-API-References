---
title: operator()()
second_title: Aspose.Slides の C++ API リファレンス
description: operator < が利用可能な型の比較関数。
type: docs
weight: 27
url: /ja/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q&, const Q&) const メソッド


[Comparison](../../../system/comparison/) operator < が利用可能な型のための関数。

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | 比較対象の型; 型変換の利用可能性を示すテンプレート。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const Q& | 比較する最初の値。 |
| y | const Q& | 比較する 2 番目の値。 |

### 戻り値

**x** が **y** より小さいとみなされる場合は true、そうでない場合は false。

## ComparerAdapter::operator()(const Q&, const Q&) const メソッド


[Comparison](../../../system/comparison/) operator < が利用できない型のための関数。

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | 比較対象の型; 型変換の利用可能性を示すテンプレート。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const Q& | 比較する最初の値。 |
| y | const Q& | 比較する 2 番目の値。 |

### 戻り値

コンパレータが設定され、**x** が **y** より小さいとみなされる場合は true、そうでない場合は false。

## 参照

* Struct [ComparerAdapter](../)
* 名前空間 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)