---
title: Sort()
second_title: Aspose.Slides for C++ API リファレンス
description: 既定の比較子を使用して、指定された配列の要素をソートします。
type: docs
weight: 742
url: /ja/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) メソッド

既定の比較子を使用して、指定された配列の要素をソートします。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 対象配列 |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) メソッド

既定の比較子を使用して、指定された配列の要素範囲をソートします。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 対象配列 |
| startIndex | int | ソートする要素範囲の開始位置を示すインデックス |
| count | int | ソートする要素範囲のサイズ |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) メソッド

指定された比較子を使用して、指定された配列の要素をソートします。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 対象配列 |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | 配列の要素を比較するために使用される IComparer<T> オブジェクト |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) メソッド

未実装。

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) メソッド

指定された比較を使用して、指定された配列の要素をソートします。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) メソッド

キーを含む配列と、対応するアイテムを含む配列の 2 つの配列を、キー配列の値に基づいてソートします。キー配列の要素は operator< を使用して比較されます。

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | **keys** 配列の要素の型 |
| TValue | **items** 配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) はキー値を含む配列です |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) は **keys** 配列のキー値にマップされたアイテムを含む配列です |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) メソッド

キーを含む配列と対応するアイテムを含む配列の 2 つの配列を、キー配列の値に基づき、既定の比較子で比較された要素を用いてソートします。

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | **keys** 配列の要素の型 |
| TValue | **items** 配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) はキー値を含む配列です |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) は **keys** 配列のキー値にマップされたアイテムを含む配列です |
| index | int | ソートする範囲の開始位置を示すインデックス |
| length | int | ソートする範囲の要素数 |

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)