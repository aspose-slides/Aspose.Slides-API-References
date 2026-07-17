---
title: LookupPrefix()
second_title: Aspose.Slides C++ API 参考
description: 返回在当前命名空间作用域中为命名空间 URI 定义的最近前缀。
type: docs
weight: 508
url: /zh/system.xml/xmltextwriter/lookupprefix/
---
## XmlTextWriter::LookupPrefix(String) 方法

返回当前命名空间作用域中为命名空间 URI 定义的最近前缀。

```cpp
String System::Xml::XmlTextWriter::LookupPrefix(String ns) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | [String](../../../system/string/) | 想要查找其前缀的命名空间 URI。 |

### 返回值

匹配的前缀。如果在当前作用域未找到匹配的命名空间 URI，则返回 **nullptr**。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlTextWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)