---
title: GetChars()
second_title: Aspose.Slides for C++ APIリファレンス
description: バイト バッファをデコードした結果得られる文字を取得します。
type: docs
weight: 66
url: /ja/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method

バイト バッファをデコードした結果得られる文字を取得します。

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| byte_count | int | 入力バッファのサイズ。 |
| chars | char_t * | [Buffer](../../../system/buffer/) に文字を格納します。 |
| char_count | int | 出力バッファのサイズ。 |

### 戻り値

書き込まれた文字数。

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

バイト バッファをデコードした結果得られる文字を取得します。

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| byte_index | int | 入力バッファのオフセット。 |
| byte_count | int | 入力バッファのサイズ。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) に文字を格納します。 |
| char_index | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれた文字数。

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

バイト バッファをデコードした結果得られる文字を取得します。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| index | int | 入力バッファのオフセット。 |
| count | int | 入力バッファのサイズ。 |

### 戻り値

[Buffer](../../../system/buffer/) のデコードされた文字。

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) method

バイト バッファをデコードした結果得られる文字を取得します。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |

### 戻り値

[Buffer](../../../system/buffer/) のデコードされた文字。

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method

バイト バッファをデコードした結果得られる文字を取得します。

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) からバイトを読み取ります。 |
| byte_count | int | 入力バッファのサイズ。 |
| chars | char_t * | [Buffer](../../../system/buffer/) に文字を格納します。 |
| char_count | int | 出力バッファのサイズ。 |

### 戻り値

書き込まれた文字数。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICUEncoding](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)