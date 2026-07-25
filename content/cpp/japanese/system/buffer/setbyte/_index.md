---
title: SetByte()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセットにバイト値を設定します。
type: docs
weight: 40
url: /ja/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) メソッド

指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセットにバイト値を設定します。

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 対象の配列 |
| index | int | 設定するバイトのゼロベースオフセット |
| value | **uint8_t** | 設定するバイト値 |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) メソッド

指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセットにバイト値を設定します。

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 対象の配列ビュー |
| index | int | 設定するバイトのゼロベースオフセット |
| value | **uint8_t** | 設定するバイト値 |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) メソッド

指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセットにバイト値を設定します。

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列要素の型 |
| N | スタック配列のサイズ |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 対象のスタック配列 |
| index | int | 設定するバイトのゼロベースオフセット |
| value | **uint8_t** | 設定するバイト値 |

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Array](../../array/)
* クラス [Buffer](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)