---
title: get_Attributes()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 XmlAttributeCollection，包含此节点的属性。
type: docs
weight: 105
url: /zh/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() 方法


返回一个 [XmlAttributeCollection](../../xmlattributecollection/)，其中包含此节点的属性。

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```


### 返回值

一个 [XmlAttributeCollection](../../xmlattributecollection/)，其中包含节点的属性。如果节点的类型是 [XmlNodeType::Element](../../xmlnodetype/)，则返回该节点的属性。否则，此方法返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttributeCollection](../../xmlattributecollection/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)