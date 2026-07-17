---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 返回映射到指定前缀的命名空间 URI。
type: docs
weight: 14
url: /zh/system.xml/ixmlnamespaceresolver/lookupnamespace/
---
## IXmlNamespaceResolver::LookupNamespace(const String\&) 方法

返回映射到指定前缀的命名空间 URI。

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupNamespace(const String &prefix)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 您想查找其命名空间 URI 的 prefix。 |

### 返回值

映射到该前缀的命名空间 URI；如果前缀未映射到任何命名空间 URI，则为 **nullptr**。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [IXmlNamespaceResolver](../)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)