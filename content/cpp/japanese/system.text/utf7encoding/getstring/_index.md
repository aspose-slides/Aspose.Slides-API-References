---
title: GetString()
second_title: Aspose.Slides for C++ API リファレンス
description: バイトバッファを文字列にデコードします。
type: docs
weight: 170
url: /ja/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) メソッド

バイトバッファを文字列にデコードします。

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| index | int | 入力バッファのオフセット。 |
| count | int | 入力バッファのサイズ。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(uint8_t *, int) メソッド

バイトバッファを文字列にデコードします。

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| byte_count | int | 入力バッファのサイズ。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) メソッド

バイトバッファを文字列にデコードします。

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) メソッド

バイトバッファを文字列にデコードします。

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) メソッド

バイトバッファを文字列にデコードします。

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) メソッド

バイトバッファを文字列にデコードします。

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) メソッド

バイトバッファを文字列にデコードします。

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| index | int | 入力バッファのオフセット。 |
| count | int | 入力バッファのサイズ。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) メソッド

バイトバッファを文字列にデコードします。

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| index | int | 入力バッファのオフセット。 |
| count | int | 入力バッファのサイズ。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) メソッド

バイトバッファを文字列にデコードします。

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| index | int | 入力バッファのオフセット。 |
| count | int | 入力バッファのサイズ。 |

### 戻り値

[String](../../../system/string/) のデコードされた文字。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [UTF7Encoding](../)
* クラス [ReadOnlySpan](../../../system/readonlyspan/)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)