---
title: LookupPrefix()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中重写时，返回当前命名空间作用域中为该命名空间 URI 定义的最近前缀。
type: docs
weight: 352
url: /zh/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) 方法

当在派生类中重写时，返回当前命名空间作用域中为该命名空间 URI 定义的最近前缀。

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | [String](../../../system/string/) | 要查找其前缀的命名空间 URI。 |

### 返回值

匹配的前缀，若在当前作用域中未找到匹配的命名空间 URI，则返回 **nullptr**。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)