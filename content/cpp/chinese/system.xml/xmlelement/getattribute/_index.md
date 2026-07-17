---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 返回具有指定名称的属性的值。
type: docs
weight: 209
url: /zh/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) 方法

返回具有指定名称的属性的值。

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要检索的属性名称。这是一个限定名称。它会与匹配节点的 **get_Name** 值进行匹配。 |

### 返回值

指定属性的值。如果未找到匹配的属性，或者属性没有指定的或默认的值，则返回空字符串。

## XmlElement::GetAttribute(String, String) 方法

返回具有指定本地名称和命名空间 URI 的属性的值。

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要检索的属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要检索的属性的命名空间 URI。 |

### 返回值

指定属性的值。如果未找到匹配的属性，或者属性没有指定的或默认的值，则返回空字符串。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)