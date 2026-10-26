---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API 参考
description: "使用 XmlNode::get_Name 的值添加一个 XmlNode。"
type: docs
weight: 27
url: /zh/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) 方法

使用其[XmlNode::get_Name](../../xmlnode/get_name/)值添加一个[XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 用于存储在[XmlNamedNodeMap](../)中的[XmlNode](../../xmlnode/)。如果映射中已经存在具有该名称的节点，则会被新节点替换。 |

### 返回值

如果**node**替换了具有相同名称的已有节点，则返回旧节点；否则，返回**nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNamedNodeMap](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)