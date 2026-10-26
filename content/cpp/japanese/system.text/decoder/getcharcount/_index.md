---
title: GetCharCount()
second_title: Aspose.Slides for C++ API リファレンス
description: バッファをデコードするために必要な文字数を取得します。
type: docs
weight: 40
url: /ja/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) メソッド


バッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| index | int | [Buffer](../../../system/buffer/) オフセット。 |
| count | int | デコードするバイト数。 |

### 戻り値

デコードするために必要な文字数。

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) メソッド


バッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| index | int | [Buffer](../../../system/buffer/) オフセット。 |
| count | int | デコードするバイト数。 |
| flush | **bool** | true の場合、計算後に内部デコーダー状態をクリアします。 |

### 戻り値

デコードするために必要な文字数。

## Decoder::GetCharCount(const uint8_t *, int, bool) メソッド


バッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| count | int | デコードするバイト数。 |
| flush | **bool** | true の場合、計算後に内部デコーダー状態をクリアします。 |

### 戻り値

デコードするために必要な文字数。

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Decoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)