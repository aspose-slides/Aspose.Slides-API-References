---
title: GetBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字バッファをエンコードした結果得られるバイトを取得します。
type: docs
weight: 66
url: /ja/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| char_index | int | 文字スライスの開始位置。 |
| char_count | int | 変換する文字数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字。 |
| char_count | int | 変換する文字数。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_count | int | 出力バッファのサイズ。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) をエンコードする。 |
| char_index | int | 文字スライスの開始位置。 |
| char_count | int | 変換する文字数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| char_index | int | 文字スライスの開始位置。 |
| char_count | int | 変換する文字数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | エンコードする文字。 |
| char_index | int | 文字スライスの開始位置。 |
| char_count | int | 変換する文字数。 |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | エンコードする文字。 |
| char_index | int | 文字スライスの開始位置。 |
| char_count | int | 変換する文字数。 |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) をエンコードする。 |
| char_index | int | 文字スライスの開始位置。 |
| char_count | int | 変換する文字数。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## UTF7Encoding::GetBytes(const String\&) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) をエンコードする。 |

### 戻り値

[Buffer](../../../system/buffer/) はエンコードされた文字の表現を保持します。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| index | int | 文字スライスの開始位置。 |
| count | int | 変換する文字数。 |

### 戻り値

[Buffer](../../../system/buffer/) はエンコードされた文字の表現を保持します。

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | エンコードする文字。 |
| index | int | 文字スライスの開始位置。 |
| count | int | 変換する文字数。 |

### 戻り値

[Buffer](../../../system/buffer/) はエンコードされた文字の表現を保持します。

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | エンコードする文字。 |
| index | int | 文字スライスの開始位置。 |
| count | int | 変換する文字数。 |

### 戻り値

[Buffer](../../../system/buffer/) はエンコードされた文字の表現を保持します。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |

### 戻り値

[Buffer](../../../system/buffer/) はエンコードされた文字の表現を保持します。

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) メソッド

文字バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字。 |
| char_count | int | 変換する文字数。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) に文字を格納する。 |
| byte_count | int | 出力バッファのサイズ。 |

### 戻り値

書き込まれたバイト数。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [UTF7Encoding](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Text](../../)
* Library [Aspose.Slides](../../../)