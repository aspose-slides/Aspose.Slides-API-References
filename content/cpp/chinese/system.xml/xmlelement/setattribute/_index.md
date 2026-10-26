---
title: SetAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 设置具有指定名称的属性的值。
type: docs
weight: 222
url: /zh/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) 方法


设置具有指定名称的属性的值。

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要创建或修改的属性的名称。这是一个限定名称。如果名称包含冒号，则会将其解析为前缀和本地名称组件。 |
| value | [String](../../../system/string/) | 要为属性设置的值。 |

## XmlElement::SetAttribute(String, String, String) 方法


设置具有指定本地名称和命名空间 URI 的属性的值。

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |
| value | [String](../../../system/string/) | 要为属性设置的值。 |

### 返回值

属性值。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)