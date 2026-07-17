---
title: idx_get()
second_title: Aspose.Slides C++ API 参考
description: 返回给定索引处的节点。
type: docs
weight: 40
url: /zh/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) 方法

返回给定索引处的节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 列表中节点的零基索引。 |

### 返回值

集合中具有指定索引的[XmlNode](../../xmlnode/)。如果索引大于或等于列表中节点的数量，则返回**nullptr**。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNodeList](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)