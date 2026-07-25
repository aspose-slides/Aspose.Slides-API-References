---
title: GetBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: バッファのエンコード結果として得られるバイトを取得します。
type: docs
weight: 53
url: /ja/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method

エンコードされたバッファから得られるバイトを取得します。

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| charIndex | int | ソース配列のオフセット。 |
| charCount | int | ソース部分配列の長さ。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 宛先バイトバッファ。 |
| byteIndex | int | 宛先バッファのオフセット。 |
| flush | **bool** | true の場合、計算後にエンコーダの内部状態をクリアします。 |

### 戻り値

書き込まれたバイト数。

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method

エンコードされたバッファから得られるバイトを取得します。

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字。 |
| charCount | int | ソース配列の長さ。 |
| bytes | **uint8_t** * | 宛先バイトバッファ。 |
| byteCount | int | 宛先バッファのサイズ。 |
| flush | **bool** | true の場合、計算後にエンコーダの内部状態をクリアします。 |

### 戻り値

書き込まれたバイト数。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)