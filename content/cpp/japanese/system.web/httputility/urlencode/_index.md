---
title: UrlEncode()
second_title: Aspose.Slides for C++ API リファレンス
description: URI フラグメントをエンコードします。
type: docs
weight: 53
url: /ja/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) メソッド

URI フラグメントをエンコードします。

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) | エンコードする URI フラグメント。 |

### 戻り値

エンコードされた URI フラグメント。

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) メソッド

URI フラグメントをエンコードします。

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) | エンコードする URI フラグメント。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディング。 |

### 戻り値

エンコードされた URI フラグメント。

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) メソッド

URI フラグメントをエンコードします。

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードする URI フラグメント。 |

### 戻り値

エンコードされた URI フラグメント。

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

URI フラグメントをエンコードします。

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードする URI フラグメント。 |
| offset | **int32_t** | バイト配列内のオフセット。 |
| count | **int32_t** | 読み取るバイト数。 |

### 戻り値

エンコードされた URI フラグメント。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [HttpUtility](../)
* クラス [Encoding](../../../system.text/encoding/)
* 名前空間 [System::Web](../../)
* ライブラリ [Aspose.Slides](../../../)