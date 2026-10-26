---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 按名称删除属性。
type: docs
weight: 235
url: /zh/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) 方法


按名称删除属性。

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要删除的属性的名称。这是一个限定名称。它会与匹配节点的 **get_Name** 值进行匹配。 |

## XmlElement::RemoveAttribute(String, String) 方法


使用指定的本地名称和命名空间 URI 删除属性。（如果被删除的属性具有默认值，则会立即被替换）。

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要删除的属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要删除的属性的命名空间 URI。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)