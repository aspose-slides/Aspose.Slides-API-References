---
title: UrlDecode()
second_title: Aspose.Slides for C++ API 參考
description: 從字串解碼 URI 片段。
type: docs
weight: 1
url: /zh-hant/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) 方法


從字串解碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 已編碼的 URI 片段。 |

### 回傳值

已解碼的 URI 片段。

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) 方法


從字串解碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 已編碼的 URI 片段。 |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | 使用的編碼。 |

### 回傳值

已解碼的 URI 片段。

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) 方法


從位元組陣列解碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 已編碼的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的編碼。 |

### 回傳值

已解碼的 URI 片段。

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) 方法


從位元組陣列解碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 已編碼的 URI 片段。 |
| offset | **int32_t** | 給定位元組陣列中的偏移量。 |
| count | **int32_t** | 要讀取的位元組數量。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的編碼。 |

### 回傳值

已解碼的 URI 片段。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [HttpUtility](../)
* 類別 [Encoding](../../../system.text/encoding/)
* 命名空間 [System::Web](../../)
* 函式庫 [Aspose.Slides](../../../)