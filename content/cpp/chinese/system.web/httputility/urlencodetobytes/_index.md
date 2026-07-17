---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API 参考
description: 对 URI 片段进行编码。
type: docs
weight: 66
url: /zh/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String&) 方法


对 URI 片段进行编码。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要编码的 URI 片段。 |

### 返回值

已编码的 URI 片段。

## HttpUtility::UrlEncodeToBytes(const String&, const System::SharedPtr\<Text::Encoding\>\&) 方法


对 URI 片段进行编码。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要编码的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的编码。 |

### 返回值

已编码的 URI 片段。

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) 方法


对 URI 片段进行编码。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要编码的 URI 片段。 |

### 返回值

已编码的 URI 片段。

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


对 URI 片段进行编码。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要编码的 URI 片段。 |
| offset | **int32_t** | 给定字节数组中的偏移量。 |
| count | **int32_t** | 要读取的字节数。 |

### 返回值

已编码的 URI 片段。

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [HttpUtility](../)
* 类 [Encoding](../../../system.text/encoding/)
* 命名空间 [System::Web](../../)
* 库 [Aspose.Slides](../../../)