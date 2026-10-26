---
title: GetCharCount()
second_title: Aspose.Slides for C++ API リファレンス
description: バイトバッファをデコードするために必要な文字数を取得します。
type: docs
weight: 261
url: /ja/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) メソッド


バイトバッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| index | int | スライスの開始位置。 |
| count | int | スライスのサイズ。 |

### 戻り値

文字数。

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) メソッド


バイトバッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |

### 戻り値

文字数。

## Encoding::GetCharCount(const uint8_t *, int) メソッド


バイトバッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| count | int | バイト数。 |

### 戻り値

文字数。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Encoding](../)
* 名前空間 [System::Text](../../)
* Library [Aspose.Slides](../../../)