---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 返回指定前缀的命名空间 URI。
type: docs
weight: 118
url: /zh/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) 方法

返回指定前缀的命名空间 URI。

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空间 URI 的前缀。若要匹配默认命名空间，请传入 [String::Empty](../../../system/string/empty/)。 |

### 返回值

如果存在映射的命名空间，则返回 **prefix** 的命名空间 URI；如果没有映射的命名空间，则返回 **nullptr**。返回的字符串已原子化。有关原子化字符串的更多信息，请参阅 [XmlNameTable](../../xmlnametable/) 类。

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlNamespaceManager](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)