---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API 參考
description: 編碼 URI 片段。
type: docs
weight: 66
url: /zh-hant/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) method


編碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要編碼的 URI 片段。 |

### 回傳值

已編碼的 URI 片段。

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


編碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要編碼的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的編碼方式。 |

### 回傳值

已編碼的 URI 片段。

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


編碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要編碼的 URI 片段。 |

### 回傳值

已編碼的 URI 片段。

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


編碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要編碼的 URI 片段。 |
| offset | **int32_t** | 給定位元組陣列中的偏移量。 |
| count | **int32_t** | 要讀取的位元組數量。 |

### 回傳值

已編碼的 URI 片段。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [HttpUtility](../)
* 類別 [Encoding](../../../system.text/encoding/)
* 命名空間 [System::Web](../../)
* 函式庫 [Aspose.Slides](../../../)