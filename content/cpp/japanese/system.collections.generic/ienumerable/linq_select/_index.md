---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの要素を変換します。
type: docs
weight: 248
url: /ja/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) メソッド

シーケンスの要素を変換します。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| ResultType | **selector** が返す値の型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 変換関数。 |

### 戻り値

selector 関数が返す要素を含む [IEnumerable](../)。

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) メソッド

シーケンスの各要素を、要素のインデックスを組み込んで新しい形に変換します。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| ResultType | **selector** が返す値の型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | 変換関数。 |

### 戻り値

selector 関数が返す要素を含む [IEnumerable](../)。

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) メソッド

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) メソッド

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IEnumerable](../)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)