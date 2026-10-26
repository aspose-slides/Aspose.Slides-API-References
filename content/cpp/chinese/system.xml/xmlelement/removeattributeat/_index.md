---
title: RemoveAttributeAt()
second_title: Aspose.Slides C++ API 参考
description: 从元素中移除具有指定索引的属性节点。（如果被移除的属性具有默认值，则会立即被替换。）
type: docs
weight: 339
url: /zh/system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt(int32_t) 方法

移除具有指定索引的属性节点。如果被移除的属性拥有默认值，它会立即被替换。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | **int32_t** | 要移除的节点的索引。第一个节点的索引为 0。 |

### 返回值

已移除的属性节点，如果给定索引处没有节点，则为 **nullptr**。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)