---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 参考
description: 在指定的参考节点之后立即插入指定的节点。
type: docs
weight: 222
url: /zh/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法

在指定的参考节点之后立即插入指定的节点。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要插入的[XmlNode](../../xmlnode/)。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 作为参考节点的[XmlNode](../../xmlnode/)。**newChild**放置在**refChild**之后。 |

### 返回值

已插入的[XmlNode](../../xmlnode/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlAttribute](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)