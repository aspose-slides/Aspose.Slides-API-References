---
title: ByteLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列のすべての要素が占めるバイト数を決定します。
type: docs
weight: 14
url: /ja/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method

指定された配列のすべての要素が占めるバイト数を決定します。

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 配列 |

### 戻り値

指定された配列のすべての要素が占めるバイト数

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method

指定された配列ビューのすべての要素が占めるバイト数を決定します。

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列ビューの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 配列ビュー |

### 戻り値

指定された配列ビューのすべての要素が占めるバイト数

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method

指定されたスタック配列のすべての要素が占めるバイト数を決定します。

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スタック配列の要素の型 |
| N | スタック配列のサイズ |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | スタック配列 |

### 戻り値

指定されたスタック配列のすべての要素が占めるバイト数

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Array](../../array/)
* クラス [Buffer](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)