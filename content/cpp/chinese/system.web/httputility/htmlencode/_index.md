---
title: HtmlEncode()
second_title: Aspose.Slides for C++ API 参考
description: 对 Html 片段进行编码。
type: docs
weight: 40
url: /zh/system.web/httputility/htmlencode/
---
## HttpUtility::HtmlEncode(const String\&) 方法

对 Html 片段进行编码。

```cpp
static String System::Web::HttpUtility::HtmlEncode(const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要编码的 Html 片段。 |

### 返回值

已编码的 Html 片段。

## HttpUtility::HtmlEncode(const SharedPtr\<Object\>\&) 方法

对 Html 片段进行编码。

```cpp
static String System::Web::HttpUtility::HtmlEncode(const SharedPtr<Object> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要编码的 Html 片段。 |

### 返回值

已编码的 Html 片段。

## HttpUtility::HtmlEncode(const String\&, const SharedPtr\<IO::TextWriter\>\&) 方法

对 Html 片段进行编码。

```cpp
static void System::Web::HttpUtility::HtmlEncode(const String &str, const SharedPtr<IO::TextWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要编码的 Html 片段。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 用于输出的 TextWriter 对象。 |

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [HttpUtility](../)
* 类 [Object](../../../system/object/)
* 类 [TextWriter](../../../system.io/textwriter/)
* 命名空间 [System::Web](../../)
* Library [Aspose.Slides](../../../)