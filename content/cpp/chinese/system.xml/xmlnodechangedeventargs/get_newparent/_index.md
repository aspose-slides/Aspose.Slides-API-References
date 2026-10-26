---
title: get_NewParent()
second_title: Aspose.Slides for C++ API 参考
description: "在操作完成后返回 XmlNode::get_ParentNode 的值。"
type: docs
weight: 40
url: /zh/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() 方法

在操作完成后返回 [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) 的值。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### 返回值

在操作完成后 **ParentNode** 的值。如果节点被移除，此方法返回 **nullptr**。对于属性节点，此方法返回 [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) 的值。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNodeChangedEventArgs](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)