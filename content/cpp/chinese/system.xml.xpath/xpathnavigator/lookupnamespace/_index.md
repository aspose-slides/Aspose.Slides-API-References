---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 返回指定前缀的命名空间 URI。
type: docs
weight: 404
url: /zh/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) 方法

返回指定前缀的命名空间 URI。

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空间 URI 的前缀。若要匹配默认命名空间，请传递 [String::Empty](../../../system/string/empty/)。 |

### 返回值

一个 [String](../../../system/string/)，其中包含分配给指定命名空间前缀的命名空间 URI；如果未为指定前缀分配命名空间 URI，则为 **nullptr**。返回的 [String](../../../system/string/) 已原子化。

## 另见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)