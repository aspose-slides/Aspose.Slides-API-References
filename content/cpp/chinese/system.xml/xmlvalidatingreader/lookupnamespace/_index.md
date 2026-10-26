---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 在当前元素的作用域中解析命名空间前缀。
type: docs
weight: 547
url: /zh/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) 方法

解析当前元素作用域中的命名空间前缀。

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空间统一资源标识符（URI）的 prefix。要匹配默认命名空间，请传入空字符串。 |

### 返回值

前缀映射到的命名空间 URI，若未找到匹配的前缀则返回 **nullptr**。

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)