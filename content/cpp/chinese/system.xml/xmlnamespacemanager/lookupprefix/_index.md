---
title: LookupPrefix()
second_title: Aspose.Slides C++ API 参考
description: 查找为给定命名空间 URI 声明的前缀。
type: docs
weight: 131
url: /zh/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) 方法

查找为给定命名空间 URI 声明的前缀。

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 要解析前缀的命名空间。 |

### 返回值

匹配的前缀。如果没有映射的前缀，方法返回 [String::Empty](../../../system/string/empty/)。如果提供了空值，则返回 **nullptr**。

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlNamespaceManager](../)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)