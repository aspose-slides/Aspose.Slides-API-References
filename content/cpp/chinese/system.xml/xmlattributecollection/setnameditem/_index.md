---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API 参考
description: "使用 XmlNode::get_Name 的结果添加一个 XmlNode。"
type: docs
weight: 14
url: /zh/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) 方法

使用其[XmlNode::get_Name](../../xmlnode/get_name/)结果添加一个[XmlNode](../../xmlnode/)。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 一个属性节点，存储在此集合中。稍后可以使用该节点的名称来访问此节点。如果集合中已经存在同名节点，则会被新节点替换；否则，节点将被追加到集合的末尾。 |

### 返回值

如果**node**替换了具有相同名称的现有节点，则返回旧节点；否则，返回添加的节点。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlAttributeCollection](../)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)