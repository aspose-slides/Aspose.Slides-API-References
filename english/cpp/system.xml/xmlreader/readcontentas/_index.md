---
title: ReadContentAs()
second_title: Aspose.Slides for C++ API Reference
description: Reads the content as an object of the type specified.
type: docs
weight: 456
url: /cpp/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const [TypeInfo](../../../system/typeinfo/)\&, [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\>) method


Reads the content as an object of the type specified.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The type of the value to be returned. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | An [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object that is used to resolve any namespace prefixes related to type conversion. For example, this can be used when converting an [XmlQualifiedName](../../xmlqualifiedname/) object to an **xs:string**. This value can be **nullptr**. |

### Return Value

The concatenated text content or attribute value converted to the requested type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
