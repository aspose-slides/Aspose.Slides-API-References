---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列内で指定された項目が最初に出現するインデックスを取得します。
type: docs
weight: 131
url: /ja/system/array/indexof/
---
## Array::IndexOf(const T\&) const method

配列内で指定された項目が最初に出現するインデックスを取得します。

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | インデックスを決定する項目 |

### 戻り値

[Index](../../index/) — 指定された項目が見つかった場合の最初の出現のインデックス、見つからない場合は -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method

配列内で指定された項目が最初に出現するインデックスを取得します。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| ArrayType | 対象配列の要素型 |
| ValueType | 配列内で検索する項目の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) で指定された項目を検索する |
| value | const [ValueType](../valuetype/)\& | インデックスを決定する項目 |

### 戻り値

[Index](../../index/) — 指定された項目が見つかった場合の最初の出現のインデックス、見つからない場合は -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method

指定したインデックスから開始して、配列内で指定された項目が最初に出現するインデックスを取得します。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| ArrayType | 対象配列の要素型 |
| ValueType | 配列内で検索する項目の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) で指定された項目を検索する |
| value | const [ValueType](../valuetype/)\& | インデックスを決定する項目 |
| startIndex | int | [Index](../../index/) で検索が開始されるインデックス |

### 戻り値

[Index](../../index/) — 指定された項目が見つかった場合の最初の出現のインデックス、見つからない場合は -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method

開始インデックスと範囲内の要素数で指定された配列の範囲内で、指定された項目が最初に出現するインデックスを取得します。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| ArrayType | 対象配列の要素型 |
| ValueType | 配列内で検索する項目の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) で指定された項目を検索する |
| value | const [ValueType](../valuetype/)\& | インデックスを決定する項目 |
| startIndex | int | [Index](../../index/) で検索が開始されるインデックス |
| count | int | 検索範囲の要素数 |

### 戻り値

[Index](../../index/) — 指定された項目が見つかった場合の最初の出現のインデックス、見つからない場合は -1

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)