---
title: VerifyXmlChars()
second_title: Aspose.Slides C++ API 参考
description: 如果字符串参数中的所有字符和代理对字符都是有效的 XML 字符，则返回传入的字符串；否则将抛出 XmlException，并提供关于遇到的第一个无效字符的信息。
type: docs
weight: 105
url: /zh/system.xml/xmlconvert/verifyxmlchars/
---
## XmlConvert::VerifyXmlChars(const String\&) 方法

如果字符串参数中的所有字符和代理对字符均为有效的 XML 字符，则返回传入的字符串；否则将抛出 XmlException，并提供遇到的第一个无效字符的信息。

```cpp
static String System::Xml::XmlConvert::VerifyXmlChars(const String &content)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | const [String](../../../system/string/)\& | [String](../../../system/string/) 包含要验证的字符。 |

### 返回值

如果字符串参数中的所有字符和代理对字符均为有效的 XML 字符，则返回传入的字符串；否则将抛出 XmlException，并提供遇到的第一个无效字符的信息。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlConvert](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)