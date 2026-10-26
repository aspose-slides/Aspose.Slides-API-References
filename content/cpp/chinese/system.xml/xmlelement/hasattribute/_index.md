---
title: HasAttribute()
second_title: Aspose.Slides C++ API 参考
description: 确定当前节点是否具有指定名称的属性。
type: docs
weight: 300
url: /zh/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) 方法


确定当前节点是否具有指定名称的属性。

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要查找的属性名称。这是一个限定名。它与匹配节点的 **get_Name** 值进行匹配。 |

### 返回值

**true** if the current node has the specified attribute; otherwise, **false**.

## XmlElement::HasAttribute(String, String) 方法


确定当前节点是否具有具有指定本地名称和命名空间 URI 的属性。

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要查找的属性本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要查找的属性的命名空间 URI。 |

### 返回值

**true** if the current node has the specified attribute; otherwise, **false**.

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)