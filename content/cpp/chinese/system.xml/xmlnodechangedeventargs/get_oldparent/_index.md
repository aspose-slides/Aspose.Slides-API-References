---
title: get_OldParent()
second_title: Aspose.Slides for C++ API 参考
description: "在操作开始前返回 XmlNode::get_ParentNode 的值。"
type: docs
weight: 27
url: /zh/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() 方法

返回 [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) 在操作开始前的值。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### 返回值

在操作开始前的 **ParentNode** 的值。如果节点没有父节点，此方法返回 **nullptr**。对于属性节点，此方法返回 [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) 值。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNodeChangedEventArgs](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)