---
title: Convert()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字をバイトに変換します。
type: docs
weight: 79
url: /ja/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

文字をバイトに変換します。

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字列。 |
| charIndex | int | 入力バッファのオフセット。 |
| charCount | int | 入力バッファのサイズ。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 目的のバイトバッファ。 |
| byteIndex | int | 目的配列のオフセット。 |
| byteCount | int | 目的配列のサイズ。 |
| flush | **bool** | true の場合、計算後に内部エンコーダの状態をクリアします。 |
| charsUsed | int\& | 読み取った文字数を格納する変数への参照。 |
| bytesUsed | int\& | 書き込んだバイト数を格納する変数への参照。 |
| completed | **bool**\& | 入力バッファが使い果たされた場合は true に、そうでなければ false に設定される変数への参照。 |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

文字をバイトに変換します。

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字列。 |
| charCount | int | 入力バッファのサイズ。 |
| bytes | **uint8_t** * | 目的のバイトバッファ。 |
| byteCount | int | 目的配列のサイズ。 |
| flush | **bool** | true の場合、計算後に内部エンコーダの状態をクリアします。 |
| charsUsed | int\& | 読み取った文字数を格納する変数への参照。 |
| bytesUsed | int\& | 書き込んだバイト数を格納する変数への参照。 |
| completed | **bool**\& | 入力バッファが使い果たされた場合は true に、そうでなければ false に設定される変数への参照。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Encoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)