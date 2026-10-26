---
title: Copy()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された要素数をソース配列から宛先配列へコピーします。
type: docs
weight: 729
url: /ja/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) メソッド

指定された要素数をソース配列から宛先配列へコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) メソッド

指定された要素数をソース配列ビューから宛先配列へコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | ソース配列ビュー |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) メソッド

指定された要素数をソース配列から宛先配列ビューへコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| dstArray | System::Details::ArrayView\<DstType\> | 宛先配列ビュー |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) メソッド

指定された要素数をソース配列ビューから宛先配列ビューへコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | ソース配列ビュー |
| dstArray | System::Details::ArrayView\<DstType\> | 宛先配列ビュー |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) メソッド

スタック上のソース配列から宛先配列へ指定された要素数をコピーします。

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | スタック上のソース配列 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) メソッド

ソース配列からスタック上の宛先配列へ指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | スタック上の宛先配列 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) メソッド

スタック上のソース配列からスタック上の宛先配列へ指定された要素数をコピーします。

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | スタック上のソース配列 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | スタック上の宛先配列 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) メソッド

ソース配列の指定したインデックスから、宛先配列の指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | ソース配列の要素の型 |
| DstType | 宛先配列の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すソース配列内のインデックスです。 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始する宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) メソッド

ソース配列ビューの指定したインデックスから、宛先配列の指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | ソース配列ビューの要素の型 |
| DstType | 宛先配列の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | ソース配列ビュー |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すソース配列ビュー内のインデックスです。 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始する宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) メソッド

ソース配列の指定したインデックスから、宛先配列ビューの指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | ソース配列の要素の型 |
| DstType | 宛先配列ビューの要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すソース配列内のインデックスです。 |
| dstArray | System::Details::ArrayView\<DstType\> | 宛先配列ビュー |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始する宛先配列ビュー内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) メソッド

ソース配列ビューの指定したインデックスから、宛先配列ビューの指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | ソース配列ビューの要素の型 |
| DstType | 宛先配列ビューの要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | ソース配列ビュー |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すソース配列ビュー内のインデックスです。 |
| dstArray | System::Details::ArrayView\<DstType\> | 宛先配列ビュー |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始する宛先配列ビュー内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) メソッド

スタック上のソース配列の指定したインデックスから、宛先配列の指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | スタック上のソース配列の要素の型 |
| DstType | 宛先配列の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | スタック上のソース配列 |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すスタック上のソース配列内のインデックスです。 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始する宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) メソッド

ソース配列の指定したインデックスから、スタック上の宛先配列の指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | ソース配列の要素の型 |
| DstType | スタック上の宛先配列の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すソース配列内のインデックスです。 |
| dstArray | System::Details::StackArray\<DstType, N\>\& | スタック上の宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始するスタック上の宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) メソッド

スタック上のソース配列の指定したインデックスから、スタック上の宛先配列の指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | スタック上のソース配列の要素の型 |
| DstType | スタック上の宛先配列の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | スタック上のソース配列 |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すスタック上のソース配列内のインデックスです。 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | スタック上の宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始するスタック上の宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) メソッド

ソース配列ビューの指定したインデックスから、スタック上の宛先配列の指定した位置へ、指定された要素数をコピーします。

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| SrcType | スタック上のソース配列の要素の型 |
| DstType | スタック上の宛先配列の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | ソース配列ビュー |
| srcIndex | **int64_t** | [Index](../../index/) は、コピーする項目範囲の開始位置を示すソース配列ビュー内のインデックスです。 |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | スタック上の宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) は、コピーされた項目の挿入を開始するスタック上の宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素数 |

## See Also

* typedef [ArrayPtr](../../arrayptr/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)