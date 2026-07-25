---
title: GetCharCount()
second_title: Aspose.Slides for C++ APIリファレンス
description: バイトバッファをデコードするために必要な文字数を取得します。
type: docs
weight: 53
url: /ja/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) メソッド

バイトバッファをデコードするために必要な文字数を取得します。

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| count | int | バイト数。 |

### 戻り値

文字数。

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) メソッド

バイトバッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| index | int | スライスの開始位置。 |
| count | int | スライスのサイズ。 |

### 戻り値

文字数。

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) メソッド

バイトバッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |

### 戻り値

文字数。

## ICUEncoding::GetCharCount(const uint8_t *, int) メソッド

バイトバッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| count | int | バイト数。 |

### 戻り値

文字数。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICUEncoding](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)