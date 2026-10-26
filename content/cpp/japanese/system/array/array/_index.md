---
title: Array()
second_title: Aspose.Slides for C++ APIリファレンス
description: 空の配列を作成します。
type: docs
weight: 1
url: /ja/system/array/array/
---
## Array::Array() コンストラクタ

空の配列を作成します。

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) コンストラクタ

初期化コンストラクタ。

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| count | int | 配列の初期サイズ |
| init | const T\& | 配列を埋めるために使用される初期値 |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) コンストラクタ

初期化コンストラクタ。

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| ValueType | 初期値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | 配列の初期サイズ |
| init | [ValueType](../valuetype/) | 配列を埋めるために使用される初期値 |

## Array::Array(int, const T) コンストラクタ

初期化コンストラクタ。

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| count | int | 配列の初期サイズ |
| inits | const T | 配列を埋めるための値 |

## Array::Array(vector_t\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::Array<T>::Array(vector_t &&value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **vector_t**\&& | 配列が取得する要素を持つ std::vector |

## Array::Array(const vector_t\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| assgn | const **vector_t**\& | 値をコピーする元の std::vector |

## Array::Array(const std::vector\<Q\>\&) コンストラクタ

[Array](../) オブジェクトを構築し、**T** と同じ型だが **UnderlyingType** とは異なる型の std::vector オブジェクトからコピーした値で埋めます。

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | コピー元となる std::vector オブジェクトの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | 値をコピーする元の std::vector |

## Array::Array(std::vector\<Q\>\&&) コンストラクタ

[Array](../) オブジェクトを構築し、**T** と同じ型だが **UnderlyingType** とは異なる型の std::vector オブジェクトからムーブされた値で埋めます。

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | ムーブ元となる std::vector オブジェクトの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | 値をムーブする元の std::vector |

## Array::Array(std::initializer_list\<UnderlyingType\>) コンストラクタ

[Array](../) オブジェクトを構築し、**UnderlyingType** 型の要素を含む指定された initializer list から値で埋めます。

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | 配列を埋める要素を含む initializer list |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) コンストラクタ

[Array](../) オブジェクトを構築し、**UnderlyingType** 型の要素を含む指定された配列から値で埋めます。

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| InitArraySize | **init** 配列の要素数。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) を構築中の配列にコピーします。 |

## Array::Array(std::initializer_list\<bool\>, int) コンストラクタ

[Array](../) オブジェクトを構築し、bool 型の要素を含む指定された initializer list から値で埋めます。

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | 配列を埋める要素を含む initializer list |

## 関連項目

* 型定義 [ValueType](../valuetype/)
* 型定義 [UnderlyingType](../underlyingtype/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)