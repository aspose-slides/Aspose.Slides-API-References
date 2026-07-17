---
title: LookupPrefix()
second_title: Aspose.Slides C++ API 参考
description: 返回为指定的命名空间 URI 声明的前缀。
type: docs
weight: 417
url: /zh/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) 方法

返回为指定的命名空间 URI 声明的前缀。

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | 用于解析前缀的命名空间 URI。 |

### 返回值

一个 [String](../../../system/string/)，其中包含分配给指定命名空间 URI 的命名空间前缀；如果未为指定的命名空间 URI 分配前缀，则为 [String::Empty](../../../system/string/empty/)。返回的 [String](../../../system/string/) 已原子化。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)