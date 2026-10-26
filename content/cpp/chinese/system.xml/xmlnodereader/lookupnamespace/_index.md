---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 解析当前元素作用域中的命名空间前缀。
type: docs
weight: 404
url: /zh/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) 方法

解析当前元素作用域中的命名空间前缀。

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空间 URI 的前缀。要匹配默认命名空间，请传入空字符串。此字符串不必先进行原子化。 |

### 返回值

前缀映射的命名空间 URI，若未找到匹配的前缀则为 **nullptr** 。

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)