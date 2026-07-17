---
title: ReadElementContentAs()
second_title: Aspose.Slides C++ API 参考
description: 将元素内容读取为请求的类型。
type: docs
weight: 586
url: /zh/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

将元素内容读取为请求的类型。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的值的类型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 用于解析与类型转换相关的任何命名空间前缀的 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 对象。 |

### 返回值

已转换为请求类型对象的元素内容。

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) 方法

检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后将元素内容读取为请求的类型。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的值的类型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 用于解析与类型转换相关的任何命名空间前缀的 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 对象。 |
| localName | [String](../../../system/string/) | 元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空间 URI。 |

### 返回值

已转换为请求类型对象的元素内容。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)