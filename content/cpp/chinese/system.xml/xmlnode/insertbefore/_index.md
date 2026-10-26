---
title: InsertBefore()
second_title: Aspose.Slides C++ API 参考
description: 将指定节点立即插入到指定的参考节点之前。
type: docs
weight: 378
url: /zh/system.xml/xmlnode/insertbefore/
---
## XmlNode::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法


将指定节点插入到指定参考节点之前。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 要插入的节点。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 参考节点。**newChild** 放置在此节点之前。 |

### 返回值

被插入的节点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)