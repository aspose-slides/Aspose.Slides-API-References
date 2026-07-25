---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の配列のすべての要素を指定された宛先配列にコピーします。要素は arrayIndex 引数で指定されたインデックスから宛先配列に挿入されます。
type: docs
weight: 118
url: /ja/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) メソッド

現在の配列のすべての要素を指定された宛先配列にコピーします。要素は arrayIndex 引数で指定されたインデックスから宛先配列に挿入されます。

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 宛先配列 |
| arrayIndex | int | [Index](../../index/) 宛先配列でコピーされた項目の挿入を開始する位置 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const メソッド

現在の配列のすべての要素を指定された宛先配列にコピーします。要素は dstIndex 引数で指定されたインデックスから宛先配列に挿入されます。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| DstType | 宛先配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/) 宛先配列でコピーされた項目の挿入を開始する位置 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const メソッド

現在の配列のすべての要素を指定された宛先配列ビューにコピーします。要素は dstIndex 引数で指定されたインデックスから宛先配列ビューに挿入されます。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| DstType | 宛先配列ビューの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 宛先配列ビュー |
| dstIndex | **int64_t** | [Index](../../index/) 宛先配列ビューでコピーされた項目の挿入を開始する位置 |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const メソッド

現在の配列から指定された位置で開始し、指定された数の要素を指定された宛先配列にコピーします。要素は dstIndex 引数で指定されたインデックスから宛先配列に挿入されます。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| DstType | 宛先配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| srcIndex | **int64_t** | [Index](../../index/) ソース配列でコピーを開始する位置 |
| dstIndex | **int64_t** | [Index](../../index/) 宛先配列でコピーされた項目の挿入を開始する位置 |
| count | **int64_t** | コピーする要素数 |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const メソッド

現在の配列から指定された位置で開始し、指定された数の要素を指定された宛先配列ビューにコピーします。要素は dstIndex 引数で指定されたインデックスから宛先配列ビューに挿入されます。

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| DstType | 宛先配列ビューの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | 宛先配列ビュー |
| srcIndex | **int64_t** | [Index](../../index/) ソース配列ビューでコピーを開始する位置 |
| dstIndex | **int64_t** | [Index](../../index/) 宛先配列ビューでコピーされた項目の挿入を開始する位置 |
| count | **int64_t** | コピーする要素数 |

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)