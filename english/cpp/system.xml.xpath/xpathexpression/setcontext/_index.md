---
title: SetContext()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, specifies the XmlNamespaceManager object to use for namespace resolution.
type: docs
weight: 53
url: /cpp/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) method


When overridden in a derived class, specifies the [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) object to use for namespace resolution.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | An [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) object to use for namespace resolution. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) method


When overridden in a derived class, specifies the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object to use for namespace resolution.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | An object that implements the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface to use for namespace resolution. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Class [XPathExpression](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)