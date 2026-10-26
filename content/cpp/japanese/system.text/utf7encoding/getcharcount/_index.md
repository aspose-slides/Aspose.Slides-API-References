---
title: GetCharCount()
second_title: Aspose.Slides for C++ API リファレンス
description: バイト バッファをデコードするために必要な文字数を取得します。
type: docs
weight: 79
url: /ja/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) メソッド

バイト バッファをデコードするために必要な文字数を取得します。

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |
| index | int | スライスの開始位置。 |
| count | int | スライスのサイズ。 |

### 戻り値

文字数。

## UTF7Encoding::GetCharCount(const uint8_t *, int) メソッド

バイト バッファをデコードするために必要な文字数を取得します。

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | デコードするバイト。 |
| count | int | バイト数。 |

### 戻り値

文字数。

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) メソッド

バイト バッファをデコードするために必要な文字数を取得します。

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

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) メソッド

バイト バッファをデコードするために必要な文字数を取得します。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | デコードするバイト。 |

### 戻り値

文字数。

## UTF7Encoding::GetCharCount(const uint8_t *, int) メソッド

バイト バッファをデコードするために必要な文字数を取得します。

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

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [UTF7Encoding](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)