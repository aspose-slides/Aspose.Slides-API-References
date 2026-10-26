---
title: Convert()
second_title: Aspose.Slides for C++ API リファレンス
description: バイトを文字に変換します。
type: docs
weight: 79
url: /ja/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) メソッド


バイトを文字に変換します。

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| byteIndex | int | 入力バッファのオフセット。 |
| byteCount | int | 入力バッファのサイズ。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 宛先文字バッファ。 |
| charIndex | int | 宛先配列のオフセット。 |
| charCount | int | 宛先配列のサイズ。 |
| flush | **bool** | true の場合、計算後に内部デコーダ状態をクリアします。 |
| bytesUsed | int\& | 読み取られたバイト数を格納する変数への参照。 |
| charsUsed | int\& | 書き込まれた文字数を格納する変数への参照。 |
| completed | **bool**\& | 入力バッファが使い果たされた場合は true、そうでない場合は false に設定される変数への参照。 |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) メソッド


バイトを文字に変換します。

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| byteCount | int | 入力バッファのサイズ。 |
| chars | char_t * | 宛先文字バッファ。 |
| charCount | int | 宛先配列のサイズ。 |
| flush | **bool** | true の場合、計算後に内部デコーダ状態をクリアします。 |
| bytesUsed | int\& | 読み取られたバイト数を格納する変数への参照。 |
| charsUsed | int\& | 書き込まれた文字数を格納する変数への参照。 |
| completed | **bool**\& | 入力バッファが使い果たされた場合は true、そうでない場合は false に設定される変数への参照。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Decoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)