---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: "返回具有指定 XmlNode::get_Name 的第一个子元素。"
type: docs
weight: 586
url: /zh/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) method

返回具有指定 [XmlNode::get_Name](../get_name/) 的第一个子元素。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要检索的元素的限定名称。 |

### 返回值

第一个匹配指定名称的 [XmlElement](../../xmlelement/)。如果没有匹配项，则返回 **nullptr**。

## XmlNode::idx_get(String, String) method

返回具有指定 [XmlNode::get_LocalName](../get_localname/) 和 [XmlNode::get_NamespaceURI](../get_namespaceuri/) 值的第一个子元素。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 元素的本地名称。 |
| ns | [String](../../../system/string/) | 元素的命名空间 URI。 |

### 返回值

第一个匹配 **localname** 和 **ns** 的 [XmlElement](../../xmlelement/)。如果没有匹配项，则返回 **nullptr**。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlElement](../../xmlelement/)
* 类 [String](../../../system/string/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)