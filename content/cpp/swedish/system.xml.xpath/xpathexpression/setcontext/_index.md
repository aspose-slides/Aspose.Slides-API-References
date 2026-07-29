---
title: SetContext()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass specificerar den XmlNamespaceManager-objektet som ska användas för namnrymdsupplösning.
type: docs
weight: 53
url: /sv/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metod


När den åsidosätts i en avledd klass specificerar den [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)-objektet som ska användas för namnrymdsupplösning.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Ett [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)-objekt som ska användas för namnrymdsupplösning. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metod


När den åsidosätts i en avledd klass specificerar den [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som ska användas för namnrymdsupplösning.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ett objekt som implementerar [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-gränssnittet för namnrymdsupplösning. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Klass [XPathExpression](../)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)