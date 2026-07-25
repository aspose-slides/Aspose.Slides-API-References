---
title: Convert()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字をバイトに変換します。
type: docs
weight: 1
url: /ja/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) メソッド


文字をバイトに変換します。

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字。 |
| charCount | int | 入力バッファのサイズ。 |
| bytes | **uint8_t** * | 出力バイトバッファ。 |
| byteCount | int | 出力配列のサイズ。 |
| flush | **bool** | true の場合、計算後にエンコーダの内部状態をクリアします。 |
| charsUsed | int\& | 読み取られた文字数を格納する変数への参照。 |
| bytesUsed | int\& | 書き込まれたバイト数を格納する変数への参照。 |
| completed | **bool**\& | 入力バッファが使い果たされた場合は true、そうでない場合は false に設定される変数への参照。 |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) メソッド


文字をバイトに変換します。

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| charIndex | int | 入力バッファのオフセット。 |
| charCount | int | 入力バッファのサイズ。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 出力バイトバッファ。 |
| byteIndex | int | 出力配列のオフセット。 |
| byteCount | int | 出力配列のサイズ。 |
| flush | **bool** | true の場合、計算後にエンコーダの内部状態をクリアします。 |
| charsUsed | int\& | 読み取られた文字数を格納する変数への参照。 |
| bytesUsed | int\& | 書き込まれたバイト数を格納する変数への参照。 |
| completed | **bool**\& | 入力バッファが使い果たされた場合は true、そうでない場合は false に設定される変数への参照。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [EncodingEncoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)