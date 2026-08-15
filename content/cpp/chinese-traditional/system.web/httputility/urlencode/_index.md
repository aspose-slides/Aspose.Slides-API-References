---
title: UrlEncode()
second_title: Aspose.Slides for C++ API 參考文件
description: 編碼 URI 片段。
type: docs
weight: 53
url: /zh-hant/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) 方法


編碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 要編碼的 URI 片段。 |

### 回傳值

已編碼的 URI 片段。

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) 方法


編碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 要編碼的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的編碼。 |

### 回傳值

已編碼的 URI 片段。

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) 方法


編碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要編碼的 URI 片段。 |

### 回傳值

已編碼的 URI 片段。

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


編碼 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要編碼的 URI 片段。 |
| offset | **int32_t** | 給定位元組陣列中的偏移量。 |
| count | **int32_t** | 要讀取的位元組數。 |

### 回傳值

已編碼的 URI 片段。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)