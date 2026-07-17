---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 参考
description: 返回映射到指定命名空间 URI 的前缀。
type: docs
weight: 27
url: /zh/system.xml/ixmlnamespaceresolver/lookupprefix/
---
## IXmlNamespaceResolver::LookupPrefix(const String\&) 方法

返回映射到指定命名空间 URI 的前缀。

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupPrefix(const String &namespaceName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceName | const [String](../../../system/string/)\& | 您希望查找其前缀的命名空间 URI。 |

### 返回值

映射到命名空间 URI 的前缀；如果命名空间 URI 未映射到前缀，则为 **nullptr**。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [IXmlNamespaceResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)