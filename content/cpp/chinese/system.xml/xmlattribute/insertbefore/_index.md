---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 参考
description: 将在指定的参考节点之前立即插入指定的节点。
type: docs
weight: 209
url: /zh/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法

将指定节点立即插入到指定的参考节点之前。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要插入的[XmlNode](../../xmlnode/)。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/)，它是参考节点。**newChild** 被放置在此节点之前。 |

### 返回值

已插入的[XmlNode](../../xmlnode/)。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlAttribute](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)