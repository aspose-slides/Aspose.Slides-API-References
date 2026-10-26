---
title: ReadStartElement()
second_title: Aspose.Slides for C++ API 参考
description: 检查当前节点是否为元素并将读取器前移到下一个节点。
type: docs
weight: 846
url: /zh/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() 方法

检查当前节点是否为元素并将读取器前移到下一个节点。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) 方法

检查当前内容节点是否为具有给定 [XmlReader::get_Name](../get_name/) 值的元素，并将读取器前移到下一个节点。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 元素的限定名称。 |

## XmlReader::ReadStartElement(String, String) 方法

检查当前内容节点是否为具有给定 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的元素，并将读取器前移到下一个节点。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 元素的本地名称。 |
| ns | [String](../../../system/string/) | 元素的命名空间 URI。 |

## 另见

* 类 [XmlReader](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)