---
title: get_BaseURI()
second_title: Aspose.Slides C++ API 参考
description: 返回节点的基础统一资源标识符 (URI)。
type: docs
weight: 183
url: /zh/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() 方法


返回该节点的基础统一资源标识符 (URI)。

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### 返回值

节点加载的位置，若节点没有基础 URI，则为 [String::Empty](../../../system/string/empty/)。 [Attribute](../../../system/attribute/) 节点的基础 URI 与其所有者元素相同。 如果属性节点没有所有者元素，get_BaseURI 将返回 [String::Empty](../../../system/string/empty/)。

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlAttribute](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)