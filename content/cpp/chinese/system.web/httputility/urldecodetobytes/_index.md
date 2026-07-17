---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API 参考
description: 从字节数组解码 URI 片段。
type: docs
weight: 14
url: /zh/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) 方法

解码来自字节数组的 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 已编码的 URI 片段。 |

### 返回值

已解码的 URI 片段。

## HttpUtility::UrlDecodeToBytes(const String\&) 方法

解码来自字符串的 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 已编码的 URI 片段。 |

### 返回值

已解码的 URI 片段。

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) 方法

解码来自字符串的 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 已编码的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用的编码。 |

### 返回值

已解码的 URI 片段。

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

解码来自字节数组的 URI 片段。

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 已编码的 URI 片段。 |
| offset | **int32_t** | 给定字节数组中的偏移量。 |
| count | **int32_t** | 要读取的字节数。 |

### 返回值

已解码的 URI 片段。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)