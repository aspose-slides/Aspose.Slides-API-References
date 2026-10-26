---
title: GetChars()
second_title: Aspose.Slides for C++ API リファレンス
description: バッファをデコードして得られる文字を取得します。
type: docs
weight: 53
url: /ja/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) メソッド

バッファをデコードして得られる文字を取得します。

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| byteIndex | int | 入力バッファのオフセット。 |
| byteCount | int | 入力バッファのサイズ。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 出力先文字バッファ。 |
| charIndex | int | 出力先配列のオフセット。 |

### 戻り値

書き込まれた文字数。

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) メソッド

バッファをデコードして得られる文字を取得します。

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| byteIndex | int | 入力バッファのオフセット。 |
| byteCount | int | 入力バッファのサイズ。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 出力先文字バッファ。 |
| charIndex | int | 出力先配列のオフセット。 |
| flush | **bool** | true の場合、計算後に内部デコーダ状態をクリアします。 |

### 戻り値

書き込まれた文字数。

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) メソッド

バッファをデコードして得られる文字を取得します。

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| byteCount | int | 入力バッファのサイズ。 |
| chars | char_t * | 出力先文字バッファ。 |
| charCount | int | 出力先配列のサイズ。 |
| flush | **bool** | true の場合、計算後に内部デコーダ状態をクリアします。 |

### 戻り値

書き込まれた文字数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Decoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)