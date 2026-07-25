---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: バイト配列から URI フラグメントをデコードします。
type: docs
weight: 14
url: /ja/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) メソッド

バイト配列から URI フラグメントをデコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードされた URI フラグメント。 |

### 戻り値

デコードされた URI フラグメント。

## HttpUtility::UrlDecodeToBytes(const String\&) メソッド

バイト文字列から URI フラグメントをデコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | エンコードされた URI フラグメント。 |

### 戻り値

デコードされた URI フラグメント。

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) メソッド

文字列から URI フラグメントをデコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | エンコードされた URI フラグメント。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディング。 |

### 戻り値

デコードされた URI フラグメント。

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

バイト配列から URI フラグメントをデコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードされた URI フラグメント。 |
| offset | **int32_t** | 指定されたバイト配列のオフセット。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

デコードされた URI フラグメント。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [HttpUtility](../)
* クラス [String](../../../system/string/)
* クラス [Encoding](../../../system.text/encoding/)
* 名前空間 [System::Web](../../)
* ライブラリ [Aspose.Slides](../../../)