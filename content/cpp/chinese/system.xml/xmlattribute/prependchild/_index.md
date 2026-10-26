---
title: PrependChild()
second_title: Aspose.Slides for C++ API 参考
description: 将指定节点添加到此节点的子节点列表的开头。
type: docs
weight: 261
url: /zh/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) 方法


添加指定节点到此节点的子节点列表的开头。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要添加的[XmlNode](../../xmlnode/)。如果它是[XmlDocumentFragment](../../xmldocumentfragment/)，则文档片段的全部内容将移动到此节点的子列表中。 |

### 返回值

已添加的[XmlNode](../../xmlnode/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlAttribute](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)