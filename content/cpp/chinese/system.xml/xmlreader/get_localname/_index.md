---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中覆盖时，获取当前节点的本地名称。
type: docs
weight: 40
url: /zh/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() 方法

当在派生类中覆盖时，获取当前节点的本地名称。

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### 返回值

当前节点的名称（已去除前缀）。例如，元素 **<bk:book>** 的 **LocalName** 为 **book**。对于没有名称的节点类型（如 **[Text](../../../system.text/)**、**Comment** 等），此方法返回 [String::Empty](../../../system/string/empty/)。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)