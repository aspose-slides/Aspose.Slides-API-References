---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API 參考
description: 從位元組陣列解碼 URI 片段。
type: docs
weight: 14
url: /zh-hant/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) 方法

從位元組陣列解碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 編碼的 URI 片段。 |

### 返回值

解碼後的 URI 片段。

## HttpUtility::UrlDecodeToBytes(const String\&) 方法

從字串解碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 編碼的 URI 片段。 |

### 返回值

解碼後的 URI 片段。

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) 方法

從字串解碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 編碼的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的編碼。 |

### 返回值

解碼後的 URI 片段。

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

從位元組陣列解碼 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 編碼的 URI 片段。 |
| offset | **int32_t** | 給定位元組陣列中的偏移量。 |
| count | **int32_t** | 要讀取的位元組數。 |

### 返回值

解碼後的 URI 片段。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)