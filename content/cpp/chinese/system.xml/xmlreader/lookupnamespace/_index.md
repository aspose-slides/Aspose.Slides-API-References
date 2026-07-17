---
title: LookupNamespace()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中重写时，解析当前元素作用域中的命名空间前缀。
type: docs
weight: 729
url: /zh/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) 方法

在派生类中重写时，解析当前元素范围内的命名空间前缀。

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空间 URI 的前缀。若要匹配默认命名空间，请传入空字符串。 |

### 返回值

前缀映射的命名空间 URI，若未找到匹配的前缀则为 **nullptr**。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)