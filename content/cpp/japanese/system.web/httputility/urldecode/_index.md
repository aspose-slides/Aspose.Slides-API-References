---
title: UrlDecode()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列から URI フラグメントをデコードします。
type: docs
weight: 1
url: /ja/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) メソッド

文字列から URI フラグメントをデコードします。

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) | エンコードされた URI フラグメント。 |

### 戻り値

デコードされた URI フラグメント。

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) メソッド

文字列から URI フラグメントをデコードします。

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../../system/string/) | エンコードされた URI フラグメント。 |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | 使用するエンコーディング。 |

### 戻り値

デコードされた URI フラグメント。

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) メソッド

バイト配列から URI フラグメントをデコードします。

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードされた URI フラグメント。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディング。 |

### 戻り値

デコードされた URI フラグメント。

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) メソッド

バイト配列から URI フラグメントをデコードします。

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | エンコードされた URI フラグメント。 |
| offset | **int32_t** | 指定されたバイト配列内のオフセット。 |
| count | **int32_t** | 読み取るバイト数。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディング。 |

### 戻り値

デコードされた URI フラグメント。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [HttpUtility](../)
* クラス [Encoding](../../../system.text/encoding/)
* 名前空間 [System::Web](../../)
* ライブラリ [Aspose.Slides](../../../)