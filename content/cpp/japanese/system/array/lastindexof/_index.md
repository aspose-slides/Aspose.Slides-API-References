---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列の開始インデックスと範囲内の要素数で指定されたアイテム範囲において、指定された項目の最後の出現位置のインデックスを決定します。
type: docs
weight: 703
url: /ja/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) メソッド

指定された開始インデックスと範囲内の要素数で指定された配列のアイテム範囲における、指定された項目の最後の出現位置のインデックスを決定します。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | [Index](../../index/) at which the search is started |
| count | int | Number of elements of the range to search in |

### 戻り値

[Index](../../index/) は、項目が見つかった場合は指定された項目の最後の出現位置、見つからなかった場合は -1 を返します。

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) メソッド

指定されたインデックスから開始する配列における、指定された項目の最後の出現位置のインデックスを決定します。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | [Index](../../index/) at which the search is started |

### 戻り値

[Index](../../index/) は、項目が見つかった場合は指定された項目の最後の出現位置、見つからなかった場合は -1 を返します。

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) メソッド

配列における、指定された項目の最後の出現位置のインデックスを決定します。

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### テンプレートパラメーター

| パラメーター | 説明 |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |

### 戻り値

[Index](../../index/) は、項目が見つかった場合は指定された項目の最後の出現位置、見つからなかった場合は -1 を返します。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)