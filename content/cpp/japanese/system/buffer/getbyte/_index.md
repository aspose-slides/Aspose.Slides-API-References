---
title: GetByte()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された型付き配列を生のバイト配列として解釈し、指定されたバイトオフセットのバイト値を取得します。
type: docs
weight: 27
url: /ja/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) メソッド

指定された型付き配列を生のバイト配列として解釈し、指定されたバイトオフセットのバイト値を取得します。

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 配列要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 対象の配列 |
| index | int | 取得するバイトのゼロベースオフセット |

### 戻り値

指定されたインデックスのバイト値

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) メソッド

指定された型付き配列を生のバイト配列として解釈し、指定されたバイトオフセットのバイト値を取得します。

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 配列ビュー要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 対象の配列ビュー |
| index | int | 取得するバイトのゼロベースオフセット |

### 戻り値

指定されたインデックスのバイト値

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) メソッド

指定された型付き配列を生のバイト配列として解釈し、指定されたバイトオフセットのバイト値を取得します。

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スタック配列要素の型 |
| N | スタック配列のサイズ |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 対象のスタック配列 |
| index | int | 取得するバイトのゼロベースオフセット |

### 戻り値

指定されたインデックスのバイト値

## 参照

* typedef [SharedPtr](../../sharedptr/)
* クラス [Array](../../array/)
* クラス [Buffer](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)