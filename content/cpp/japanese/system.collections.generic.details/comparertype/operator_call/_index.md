---
title: operator()()
second_title: Aspose.Slides for C++ API リファレンス
description: IComparable インターフェイスを実装する値型を比較します。
type: docs
weight: 1
url: /ja/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const メソッド


[IComparable](../../../system/icomparable/) インターフェイスを実装する値型を比較します。

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Q | 比較する型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | const Q\& | 左辺の値。 |
| b | const Q\& | 右辺の値。 |

### 戻り値

**a** が **b** 未満と見なされた場合は true、そうでなければ false。

## ComparerType::operator()(const Q\&, const Q\&) const メソッド


[IComparable](../../../system/icomparable/) インターフェイスを実装しないプリミティブ型およびオブジェクトを比較します。

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Q | 比較する型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | const Q\& | 左辺の値。 |
| b | const Q\& | 右辺の値。 |

### 戻り値

**a** が **b** 未満と見なされた場合は true、そうでなければ false。

## ComparerType::operator()(const Q\&, const Q\&) const メソッド


浮動小数点型を比較します。

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Q | 比較する型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | const Q\& | 左辺の値。 |
| b | const Q\& | 右辺の値。 |

### 戻り値

**a** が **b** 未満と見なされた場合は true、そうでなければ false。

## 参照

* クラス [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* 名前空間 [System::Collections::Generic::Details](../../)
* ライブラリ [Aspose.Slides](../../../)