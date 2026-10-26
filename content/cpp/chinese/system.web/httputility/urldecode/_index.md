---
title: UrlDecode()
second_title: Aspose.Slides for C++ API 参考
description: 从字符串解码 URI 片段。
type: docs
weight: 1
url: /zh/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) 方法

从字符串解码 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | 已编码的 URI 片段。 |

### 返回值

已解码的 URI 片段。

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) 方法

从字符串解码 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | 已编码的 URI 片段。 |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | 要使用的编码。 |

### 返回值

已解码的 URI 片段。

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) 方法

从字节数组解码 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 已编码的 URI 片段。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的编码。 |

### 返回值

已解码的 URI 片段。

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) 方法

从字节数组解码 URI 片段。

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 已编码的 URI 片段。 |
| offset | **int32_t** | 给定字节数组中的偏移量。 |
| count | **int32_t** | 要读取的字节数。 |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的编码。 |

### 返回值

已解码的 URI 片段。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [HttpUtility](../)
* 类 [Encoding](../../../system.text/encoding/)
* 命名空间 [System::Web](../../)
* 库 [Aspose.Slides](../../../)