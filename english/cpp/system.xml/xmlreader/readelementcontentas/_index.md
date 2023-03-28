---
title: ReadElementContentAs()
second_title: Aspose.Slides for C++ API Reference
description: Reads the element content as the requested type.
type: docs
weight: 586
url: /cpp/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const [TypeInfo](../../../system/typeinfo/)\&, [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\>) method


Reads the element content as the requested type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The type of the value to be returned. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | An [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object that is used to resolve any namespace prefixes related to type conversion. |

### Return Value

The element content converted to the requested typed object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlReader::ReadElementContentAs(const [TypeInfo](../../../system/typeinfo/)\&, [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\>, [String](../../../system/string/), [String](../../../system/string/)) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the element content as the requested type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The type of the value to be returned. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | An [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object that is used to resolve any namespace prefixes related to type conversion. |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The element content converted to the requested typed object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
