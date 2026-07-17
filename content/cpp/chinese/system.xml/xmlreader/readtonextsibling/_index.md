---
title: ReadToNextSibling()
second_title: Aspose.Slides C++ API 参考
description: 将 XmlReader 前进到具有指定限定名称的下一个兄弟元素。
type: docs
weight: 924
url: /zh/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) 方法


将 [XmlReader](../) 前进到具有指定限定名称的下一个兄弟元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 您希望移动到的兄弟元素的限定名称。 |

### 返回值

**true** 如果找到匹配的兄弟元素；否则为 **false**。如果未找到匹配的兄弟元素，[XmlReader](../) 将定位在父元素的结束标签上（[XmlReader::get_NodeType](../get_nodetype/) 值为 [XmlNodeType::EndElement](../../xmlnodetype/)）。

## XmlReader::ReadToNextSibling(String, String) 方法


将 [XmlReader](../) 前进到具有指定本地名称和命名空间 URI 的下一个兄弟元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 您希望移动到的兄弟元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 您希望移动到的兄弟元素的命名空间 URI。 |

### 返回值

**true** 如果找到匹配的兄弟元素；否则为 **false**。如果未找到匹配的兄弟元素，[XmlReader](../) 将定位在父元素的结束标签上（[XmlReader::get_NodeType](../get_nodetype/) 值为 [XmlNodeType::EndElement](../../xmlnodetype/)）。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)