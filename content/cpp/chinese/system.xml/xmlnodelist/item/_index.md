---
title: Item()
second_title: Aspose.Slides for C++ API 参考
description: 检索给定索引处的节点。
type: docs
weight: 14
url: /zh/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) 方法

检索给定索引处的节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 零基索引，指向节点列表中的位置。 |

### 返回值

具有指定索引的 [XmlNode](../../xmlnode/)。如果 **index** 大于或等于列表中节点的数量，则返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNodeList](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)