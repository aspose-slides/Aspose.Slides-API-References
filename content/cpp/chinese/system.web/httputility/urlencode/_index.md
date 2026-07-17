---
title: UrlEncode()
second_title: Aspose.Slides for C++ API 参考
description: 对 URI 片段进行编码。
type: docs
weight: 53
url: /zh/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) 方法


对 URI 片段进行编码。

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 要编码的 URI 片段。 |

### 返回值

已编码的 URI 片段。

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) 方法


对 URI 片段进行编码。

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 要编码的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的编码。 |

### 返回值

已编码的 URI 片段。

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) 方法


对 URI 片段进行编码。

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要编码的 URI 片段。 |

### 返回值

已编码的 URI 片段。

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


对 URI 片段进行编码。

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要编码的 URI 片段。 |
| offset | **int32_t** | 给定字节数组中的偏移量。 |
| count | **int32_t** | 要读取的字节数。 |

### 返回值

已编码的 URI 片段。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)