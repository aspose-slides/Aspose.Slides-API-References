---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API リファレンス
description: URI フラグメントをエンコードします。
type: docs
weight: 66
url: /ja/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) メソッド

URI フラグメントをエンコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | エンコードする URI フラグメントです。 |

### 戻り値

エンコードされた URI フラグメントです。

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) メソッド

URI フラグメントをエンコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | エンコードする URI フラグメントです。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディングです。 |

### 戻り値

エンコードされた URI フラグメントです。

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) メソッド

URI フラグメントをエンコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードする URI フラグメントです。 |

### 戻り値

エンコードされた URI フラグメントです。

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

URI フラグメントをエンコードします。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードする URI フラグメントです。 |
| offset | **int32_t** | 指定されたバイト配列のオフセットです。 |
| count | **int32_t** | 読み取るバイト数です。 |

### 戻り値

エンコードされた URI フラグメントです。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [HttpUtility](../)
* クラス [Encoding](../../../system.text/encoding/)
* 名前空間 [System::Web](../../)
* Library [Aspose.Slides](../../../)