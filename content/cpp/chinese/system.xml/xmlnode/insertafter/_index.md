---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 参考
description: 在指定的参考节点之后立即插入指定的节点。
type: docs
weight: 391
url: /zh/system.xml/xmlnode/insertafter/
---
## XmlNode::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法

在指定的参考节点之后立即插入指定的节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 要插入的节点。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 参考节点。**newChild** 在 **refChild** 之后放置。 |

### 返回值

被插入的节点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)