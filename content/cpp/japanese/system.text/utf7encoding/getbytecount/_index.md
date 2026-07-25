---
title: GetByteCount()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字バッファをエンコードするために必要な文字数を取得します。
type: docs
weight: 157
url: /ja/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) メソッド


文字バッファをエンコードするために必要な文字数を取得します。

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | 文字バッファ。 |
| count | int | [Buffer](../../../system/buffer/) サイズ。 |

### 戻り値

必要なバッファサイズ。

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) メソッド


文字バッファをエンコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 文字バッファ。 |
| index | int | スライス開始位置。 |
| count | int | スライスサイズ。 |

### 戻り値

必要なバッファサイズ。

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) メソッド


文字バッファをエンコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 文字バッファ。 |
| index | int | スライス開始位置。 |
| count | int | スライスサイズ。 |

### 戻り値

必要なバッファサイズ。

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) メソッド


文字バッファをエンコードするために必要な文字数を取得します。

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 文字バッファ。 |
| index | int | スライス開始位置。 |
| count | int | スライスサイズ。 |

### 戻り値

必要なバッファサイズ。

## UTF7Encoding::GetByteCount(const String\&) メソッド


文字列をエンコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) をエンコードする。 |

### 戻り値

必要なバッファサイズ。

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) メソッド


文字バッファをエンコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 文字バッファ。 |

### 戻り値

必要なバッファサイズ。

## UTF7Encoding::GetByteCount(const char_t *, int) メソッド


文字バッファをエンコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | 文字バッファ。 |
| count | int | [Buffer](../../../system/buffer/) サイズ。 |

### 戻り値

必要なバッファサイズ。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [UTF7Encoding](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)