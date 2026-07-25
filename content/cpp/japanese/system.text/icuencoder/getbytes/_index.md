---
title: GetBytes()
second_title: Aspose.Slides の C++ API リファレンス
description: バッファをエンコードした結果得られるバイトを取得します。
type: docs
weight: 53
url: /ja/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method

バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコード対象の文字列。 |
| charIndex | int | 元配列のオフセット。 |
| charCount | int | 元部分配列の長さ。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 宛先のバイトバッファ。 |
| byteIndex | int | 宛先バッファのオフセット。 |
| flush | **bool** | true の場合、計算後に内部エンコーダ状態をクリアします。 |

### 戻り値

書き込まれたバイト数。

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method

バッファをエンコードした結果得られるバイトを取得します。

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコード対象の文字列。 |
| charCount | int | 元配列の長さ。 |
| bytes | **uint8_t** * | 宛先のバイトバッファ。 |
| byteCount | int | 宛先バッファのサイズ。 |
| flush | **bool** | true の場合、計算後に内部エンコーダ状態をクリアします。 |

### 戻り値

書き込まれたバイト数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ICUEncoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)