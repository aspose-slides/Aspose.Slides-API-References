---
title: HtmlDecode()
second_title: Aspose.Slides C++ API 参考
description: 解码 Html 片段。
type: docs
weight: 27
url: /zh/system.web/httputility/htmldecode/
---
## HttpUtility::HtmlDecode(const String\&) 方法

解码 Html 片段。

```cpp
static String System::Web::HttpUtility::HtmlDecode(const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要解码的 Html 片段。 |

### 返回值

已解码的 Html 片段。

## HttpUtility::HtmlDecode(const String\&, const SharedPtr\<IO::TextWriter\>\&) 方法

解码 Html 片段。

```cpp
static void System::Web::HttpUtility::HtmlDecode(const String &str, const SharedPtr<IO::TextWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要解码的 Html 片段。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 用于输出的 TextWriter 对象。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [HttpUtility](../)
* 类 [TextWriter](../../../system.io/textwriter/)
* 命名空间 [System::Web](../../)
* 库 [Aspose.Slides](../../../)