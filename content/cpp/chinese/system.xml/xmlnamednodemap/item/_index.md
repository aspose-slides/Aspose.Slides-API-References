---
title: Item()
second_title: Aspose.Slides for C++ API 参考
description: 在 XmlNamedNodeMap 中检索指定索引处的节点。
type: docs
weight: 53
url: /zh/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) 方法

检索 [XmlNamedNodeMap](../) 中指定索引处的节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要从 [XmlNamedNodeMap](../) 检索的节点的索引位置。索引从零开始计数；因此，第一个节点的索引为 0，最后一个节点的索引为 [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### 返回值

指定索引处的 [XmlNode](../../xmlnode/)。如果 **index** 小于 0 或大于等于 [XmlNamedNodeMap::get_Count](../get_count/) 值，则返回 **nullptr**。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNamedNodeMap](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)