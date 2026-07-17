---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ API 参考
description: 将 XmlReader 前进到具有指定限定名称的下一个后代元素。
type: docs
weight: 911
url: /zh/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) 方法

将 [XmlReader](../) 前进到具有指定限定名称的下一个后代元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 您希望移动到的元素的限定名称。 |

### 返回值

**true** 如果找到匹配的后代元素；否则 **false**。如果未找到匹配的子元素，[XmlReader](../) 将定位在该元素的结束标签（[XmlReader::get_NodeType](../get_nodetype/) 值为 [XmlNodeType::EndElement](../../xmlnodetype/)）。如果在调用 [XmlReader::ReadToDescendant(String)](./) 时 [XmlReader](../) 未定位在元素上，则此方法返回 **false**，且 [XmlReader](../) 的位置不变。

## XmlReader::ReadToDescendant(String, String) 方法

将 [XmlReader](../) 前进到具有指定本地名称和命名空间 URI 的下一个后代元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 您希望移动到的元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 您希望移动到的元素的命名空间 URI。 |

### 返回值

**true** 如果找到匹配的后代元素；否则 **false**。如果未找到匹配的子元素，[XmlReader](../) 将定位在该元素的结束标签（[XmlReader::get_NodeType](../get_nodetype/) 值为 [XmlNodeType::EndElement](../../xmlnodetype/)）。如果在调用 [XmlReader::ReadToDescendant(String,String)](./) 时 [XmlReader](../) 未定位在元素上，则此方法返回 **false**，且 [XmlReader](../) 的位置不变。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)