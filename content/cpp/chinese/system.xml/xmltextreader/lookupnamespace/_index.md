---
title: LookupNamespace()
second_title: Aspose.Slides C++ API 参考
description: 在当前元素的作用域中解析命名空间前缀。
type: docs
weight: 612
url: /zh/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) 方法

解析当前元素范围内的命名空间前缀。

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空间 URI 的前缀。若要匹配默认命名空间，请传入空字符串。此字符串不必进行原子化。 |

### 返回值

前缀映射到的命名空间 URI，若未找到匹配的前缀，则为 **nullptr**。

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)