---
title: ReadNode()
second_title: Aspose.Slides for C++ API 参考
description: 根据 XmlReader 中的信息创建一个 XmlNode 对象。读取器必须定位在节点或属性上。
type: docs
weight: 495
url: /zh/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) 方法


基于 [XmlReader](../../xmlreader/) 中的信息创建一个 [XmlNode](../../xmlnode/) 对象。读取器必须定位在节点或属性上。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML 源。 |

### 返回值

如果不存在更多节点，则返回新的 [XmlNode](../../xmlnode/) 或 **nullptr**。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlReader](../../xmlreader/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)