---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，创建该节点的副本。
type: docs
weight: 456
url: /zh/system.xml/xmlnode/clonenode/
---
## XmlNode::CloneNode(bool) 方法

在派生类中重写时，创建该节点的副本。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::CloneNode(bool deep)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 仅克隆节点本身。 |

### 返回值

克隆的节点。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)