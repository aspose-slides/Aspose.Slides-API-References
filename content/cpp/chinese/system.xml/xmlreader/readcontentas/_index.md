---
title: ReadContentAs()
second_title: Aspose.Slides for C++ API 参考
description: 将内容读取为指定类型的对象。
type: docs
weight: 456
url: /zh/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

将内容读取为指定类型的对象。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的值的类型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 用于解析与类型转换相关的任何命名空间前缀的 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 对象。例如，在将 [XmlQualifiedName](../../xmlqualifiedname/) 对象转换为 **xs:string** 时可以使用此对象。此值可以为 **nullptr**。 |

### 返回值

连接的文本内容或属性值，已转换为请求的类型。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)